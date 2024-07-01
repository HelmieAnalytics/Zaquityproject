# Zaquity
This package provides functionality for fetching and processing stock data for securities listed on the Johannesburg Stock Excchange.

It includes functions for fetching historical stock data, fetching ticker data from the MarketStack API, and cleaning stock data by removing outliers.

Modules:
    jse_data module: Fetches historical stock data for a list of symbols and saves it to individual CSV files.
    jse_ticker module: Fetches ticker data from the MarketStack API and processes it.
    process_data module: Processes stock CSV files in the specified folder to remove outliers.

Functions:
    jse_data.get_data(symbols, start, end, output_folder): Fetches historical stock data for a list of symbols and saves it to individual CSV files.
    jse_ticker.get_tickers(access_key): Fetches ticker data from the MarketStack API and processes it.
    process_data.clean(csv_folder_path): Processes stock CSV files in the specified folder to remove outliers.
"""
