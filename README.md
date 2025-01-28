# Background
The dataset appears to contain historical stock market data for the Dow Jones Industrial Average (DJIA). It includes seven columns: "Date," which records the trading date; "Open," showing the opening value of the DJIA for each trading day; "High," representing the highest value during the day; "Low," capturing the lowest value; "Close," indicating the closing value; "Volume," which reflects the total number of shares traded; and "Adj Close," the adjusted closing value that accounts for dividends and splits. This dataset is utilized in an ETL (Extract, Transform, Load) process to analyze historical trends of the Dow Jones Industrial Average (DJIA). 

# Extract
During the extraction phase, the raw data are loaded from the provided CSV file. Before, do the extraction phrase, import libraries needed, which are pathlib, numpy, pandas, matplotlib, pyplot, ticker and sqlite3.
After that, import the CSV file.

# Transformation
In the transformation stage, the date column is changed its format into a proper datetime format, and the data is deriving additional metrics which are daily returns and volatility.
