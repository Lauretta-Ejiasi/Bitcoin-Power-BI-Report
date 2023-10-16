# Bitcoin-Power-BI-Report
Bitcoin Power BI Report

**Context of Dataset Used**
This is a report on Bitcoin wich is the longest running and most well known cryptocurrency, first released as open source in 2009 by the anonymous Satoshi Nakamoto. Bitcoin serves as a decentralized medium of digital exchange, with transactions verified and recorded in a public distributed ledger (the blockchain) without the need for a trusted record keeping authority or central intermediary. Transaction blocks contain a SHA-256 cryptographic hash of previous transaction blocks, and are thus "chained" together, serving as an immutable record of all transactions that have ever occurred. As with any currency/commodity on the market, bitcoin trading and financial instruments soon followed public adoption of bitcoin and continue to grow. Included here is historical bitcoin market data at 1-min intervals for select bitcoin exchanges where trading took place.


This report provides an analysis of Bitcoin exchange data from Jan 2012 to March 2021, with minute-by-minute updates of OHLC (Open, High, Low, Close), volume in BTC and indicated currency, and weighted bitcoin price. Timestamps are in Unix time. 
Here are summary of steps used for data analysis in Power BI:
1. Data Cleaning: To ensure data accuracy and consistency, the following data cleaning steps were performed:
•	Removed duplicate entries
•	Filled NaN values with appropriate values
•	Handled missing timestamps and converted the time stamp column using the unix epoch time stamp of (1970, 1, 1, 0,0,0) 
•	Checked for and removed outliers

2. Data Analysis : To gain insights into the behavior and performance of Bitcoin exchanges over time, the following data analysis steps were performed:
•	Calculated summary statistics such as mean, median, and standard deviation on the OHLC, volume, and weighted price data
•	Created visualizations such as line charts, area chart, bar chart, and column charts to visualize trends in the OHLC, volume, and weighted price data over time
•	Used time series analysis techniques to identify patterns in the OHLC, volume, and weighted price data, such as seasonality or cyclicality
•	Compared the OHLC, volume, and weighted price data across different exchanges to identify differences in behavior and performance.

3. Data Manipulation: To enable more advanced analysis of the Bitcoin exchange data, the following data manipulation steps were performed:
•	Aggregated the minute-by-minute OHLC, volume, and weighted price data to daily intervals
•	Calculated moving averages of the OHLC and weighted price data over different time periods to identify trends and patterns
•	Created calculated fields based on existing fields in the dataset to enable more advanced analysis, such as volatility or rate of change
•	Joined tables from different sources (e.g., exchange data and macroeconomic data) to enable more comprehensive analysis of the Bitcoin market


**Conclusion**
By performing these data cleaning, analysis, and manipulation tasks in Power BI, i was able to gain valuable insights into Bitcoin exchange data from Jan 2012 to March 2021. These insights can be used to make informed decisions about Bitcoin trading or investments.
The associated Power BI snapshot report and CSV file can be found in my GitHub repository under the "Bitcoin Exchange Data Analysis Report".
