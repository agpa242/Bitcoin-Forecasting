# Bitcoin-Forecasting

## About the Dataset

Bitcoin, the most well-known and oldest cryptocurrency, was introduced in 2009 by the mysterious Satoshi Nakamoto. Operating in a decentralized manner, Bitcoin facilitates digital exchange without requiring a central clearinghouse or trusted authority. Transactions are validated and recorded on a public distributed ledger. Transaction blocks are linked together to form an immutable record of all past transactions, secured by a SHA-256 cryptographic hash. The public adoption of Bitcoin led to the development of trading and financial instruments around it, similar to traditional currencies or commodities. This dataset provides historical market data from various Bitcoin exchanges, offering insights into trading patterns.

CSV files containing minute-by-minute updates of OHLC (Open, High, Low, Close), volume in BTC and currency, and weighted Bitcoin prices are available for select Bitcoin exchanges. The data spans from January 2012 through March 2021, using Unix time for timestamps. Timestamps with no transactions or activity are marked as NaN. Missing timestamps might be due to technical issues during data reporting or gathering. Efforts have been made to remove duplicates and ensure accuracy, but use the data at your own risk.

The dataset can be found at: [Bitcoin Historical Data](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)

## Kernel Structure

This Kernel is divided into two parts:

- **Data Exploration**
- **Time Series Analysis**

These sections aim to provide insights into the Bitcoin historical data, its trends, and patterns, along with performing time series analysis to gain a deeper understanding of the dataset.
