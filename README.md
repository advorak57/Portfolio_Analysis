# Quantitative_Analysis
Performed data cleaning and caluculations on provided portfolio data for whale and algorithmic portfolios to determine performance, risk, and volatility. 
# Tasks
 - Prepared the Data
 - Performed Quantitative Analysis
 - Created a Custom Portfolio

# Used Pandas to read the following CSV files into DataFrames. Converted the dates to a DateTimeIndex.

whale_returns.csv: Contains returns of some famous "whale" investors' portfolios.

algo_returns.csv: Contains returns from the in-house trading algorithms from your company.

sp500_history.csv: Contains historical closing prices of the S&P 500 Index.

Identified and removed null values.

Removed any non-numeric values (e.g., dollar signs) from the DataFrames and converted the data types as needed.

The whale portfolios and algorithmic portfolio CSV files contain daily returns, but the S&P 500 CSV file contains closing prices. Converted the S&P 500 closing prices to daily returns.

Joined Whale Returns, Algorithmic Returns, and the S&P 500 Returns into a single DataFrame with columns for each portfolio's returns.

# Performed Quantitative Analysis
Analyzed the data to determine if any of the portfolios outperform the stock market (that is, the S&P 500). Specifically, did performance analysis and a risk analysis, and then calculated rolling statistics and Sharpe ratios.

# Performance Analysis
Calculated and plotted daily returns of all portfolios.

Calculated and plotted cumulative returns for all portfolios. Determined portfolios that outperformed the S&P 500?

# Risk Analysis
Created a box plot for each of the returns.

Calculated the standard deviation for each portfolio.

Determined which portfolios are riskier than the S&P 500.

Calculated the annualized standard deviation.

# Rolling Statistics
Calculated and plotted the rolling standard deviation for all portfolios, using a 21-day window.

Calculated and plot the correlation between each stock to determine which portfolios mimic the S&P 500.

Chose one portfolio, then calculated and plotted the 60-day rolling beta between that portfolio and the S&P 500.

# Rolling Statistics Challenge: Exponentially Weighted Average
Showed an alternative method to calculate a rolling window to find the exponentially weighted moving average. This is like a moving window average, but it assigns greater importance to more recent observations. 

#Sharpe Ratios

Using the daily returns, calculated the Sharpe ratios and visualized them in a bar plot.

Determined whether the algorithmic strategies outperformed both the market (S&P 500) and the whales portfolios.

#Created a Custom Portfolio

Used Google Sheets Links to an external site.and its built-in GOOGLEFINANCE function to choose 5 stocks for 'My Portfolio'.

Downloaded the data as CSV files and calculated the portfolio returns.

Calculated the weighted returns for portfolio, assuming equal number of shares per stock.

# Added portfolio returns to the DataFrame with the other portfolios.

# Ran the following analyses:

Calculated the annualized standard deviation.
Calculated and plotted the rolling standard deviation with a 21-day window.
Calculated and plotted the correlation.
Calculated and plotted beta for your portfolio compared to the S&P 60 TSX.
Calculated the Sharpe ratios and generated a bar plot.

All to answer how my custom portfolio performed relative to others. 
