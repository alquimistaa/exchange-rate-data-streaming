** Daily FX Rate Tracker and Updater Pipeline (Open Exchange Rates API) ** (2024 Data)
This project is an automated data pipeline that fetches daily USD-based foreign exchange rates via the Open Exchange Rates API and stores them in a local CSV file. It also updates and corrects data for the previous four days to ensure accuracy. The solution leverages Python, pandas, and requests to automate data fetching, updating, and storage.
During data recording, duplicate entries for the same date are prevented, and recent historical data is corrected to build an up-to-date and reliable dataset.
