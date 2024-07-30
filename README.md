# S&P 500 Stocks DataSet 

### https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks?select=sp500_stocks.csv

### About dataset
The Standard and Poor's 500 or S&P 500 is the most famous financial benchmark in the world.

This stock market index tracks the performance of 500 large companies listed on stock exchanges in the United States. As of December 31, 2020, more than $5.4 trillion was invested in assets tied to the performance of this index.

Because the index includes multiple classes of stock of some constituent companies—for example, Alphabet's Class A (GOOGL) and Class C (GOOG) - there are actually 505 stocks in the gauge.

### Dataset description
The dataset unites 3 subsets, each in separate csv files:
### 1) sp500_stocks.csv
The stocks subset contains 1843998 rows and 7 columns:
-  **Date**: the date from 2010-01-04 to 2024-07-29 
- **Symbol**: Company Symbol/Ticker
- **Adj Close**: Similar to the price at market closure, yet also takes into account company actions such as dividends and splits
- **Close**: Price at market closure
- **High**: Maximum value of period
- **Low**: Minimum value of period
- **Open**: Price at market opening
- **Volume**: Volume traded

### 2) sp500_index.csv
The index subset contains 2517 rows and 2 columns:
-  **Date**: the date from 2014-07-28 to 2024-07-26
- **S&P500**: S&P500 index

### 3) sp500_companies.csv
The companies subset contains 503 rows and 16 columns:
- **Exchange**: The stock exchange where the company is listed.
- **Symbol**: The stock ticker symbol.
- **Shortname**: The short name of the company.
- **Longname**: The full name of the company.
- **Sector**: The sector to which the company belongs.
- **Industry**: The industry within the sector.
- **Currentprice**: The current price of the stock.
- **Marketcap**: The market capitalization of the company.
- **Ebitda**: Earnings before interest, taxes, depreciation, and amortization.
- **Revenuegrowth**: The revenue growth rate of the company.
- **City**: The city where the company is headquartered.
- **State**: The state where the company is headquartered.
- **Country**: The country where the company is headquartered.
- **Fulltimeemployees**: The number of full-time employees.
- **Longbusinesssummary**: A detailed summary of the company's business.
- **Weight**: The weight of the company in the S&P 500 index.
