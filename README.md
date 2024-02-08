# Equity Portfolio Management Project

## Project Overview

This project aims to manage an equity portfolio using data from the year 2018 for 10 selected stocks. The primary objective is to implement two different trading strategies and compare their effectiveness in maximizing portfolio returns. Additionally, the project involves the creation of a high-tech index for benchmarking purposes and the analysis of currency conversion impact on portfolio performance.

### Data Preparation

1. **Data Acquisition:**
   - Download historical daily data for the entire 2018 for the 10 stocks:
     - IBM, MSFT, GOOG, AAPL, AMZN, FB, NFLX, TSLA, ORCL, SAP.
   - Retrieve data from Yahoo Finance or similar sources, ensuring availability of "Close" and "Adj Close" values.

2. **Portfolio Initialization:**
   - Start managing a $5 million fund on January 2, 2018.
   - Allocate $1 million to each of the 5 selected stocks: IBM, MSFT, GOOG, AAPL, AMZN.
   - Maintain the remaining cash in a zero-interest cash account.

### Trading Strategies

1. **5 Days Rebalancing - Buying Low:**
   - Rebalance the portfolio every 5 days based on the stocks that experienced the largest percentage drop in "Adj Close" prices.
   - Sell current holdings and reinvest in the stocks that dropped the most, maximizing shares bought with available cash.

2. **5 Days Rebalancing - Buying High:**
   - Rebalance the portfolio every 5 days based on the stocks that experienced the largest percentage surge in "Adj Close" prices.
   - Sell current holdings and reinvest in the stocks with the highest price momentum, expecting the trend to continue.

### Portfolio Management

- Track portfolio performance over time, adjusting holdings based on the selected trading strategies.
- Account for stock dividends and adjust cash holdings accordingly.
- Rebalance the portfolio every 5 days as per the chosen strategy.

### Performance Evaluation

1. **Comparison with High-Tech Index:**
   - Create a high-tech index using the daily average of the 10 stocks' "Close" prices.
   - Compare portfolio performance with the index to assess relative returns.

2. **Currency Conversion Analysis:**
   - Download historical USD/JPY exchange rate data for 2018.
   - Convert portfolio value from USD to JPY and analyze impact on MTM.

3. **Optimization of Rebalancing Intervals:**
   - Experiment with different rebalancing intervals to identify the optimal frequency for maximizing returns by December 31, 2018.

### Details
- Includes plots of the portfolio's MTM curve, comparison with the high-tech index, and USD/JPY conversion analysis.
