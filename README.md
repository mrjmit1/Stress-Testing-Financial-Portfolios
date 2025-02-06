# Stress-Testing-Financial-Portfolios
Data from Kaggle: https://www.kaggle.com/datasets/camnugent/sandp500/data

# S&P 500 Stock Data Overview

**Dataset Description:**
The dataset provides historical stock prices for S&P 500 companies over the last five years, facilitating analysis and model building for financial insights. It was compiled using a script from GitHub and includes updates as of February 2018.

**Content and Formats:**
- **Merged Data:** `all_stocks_5yr.csv` - Combined data for all stocks.
- **Individual Data:** `individual_stocks_5yr` folder - Separate files for each stock, named by their ticker.

**Columns:**
- **Date:** Stock price date (yy-mm-dd format).
- **Open:** Opening price in USD.
- **High:** Highest price of the day.
- **Low:** Lowest price of the day.
- **Close:** Closing price.
- **Volume:** Number of shares traded.
- **Name:** Stock's ticker symbol.

**Data Source and Tools:**
- **Data Source:** The Investor's Exchange API.
- **Tools Used:** Kaggle, GitHub, pandas_datareader, and The Market.

**Usage and Analysis:**
- **Visualization Opportunities:** Visualize price changes, compare stocks, and generate new metrics.
- **Analytical Potential:** Calculate stock statistics like volatility and moving averages.
- **Challenge:** Develop models to outperform the market and enable informed trades.

**Scenario Analysis for Portfolio Stress Testing:**
- **Financial Crisis Scenario:** Evaluate portfolio performance during a significant economic downturn.
  - **Key Assumptions:** Market drop (e.g., 30% decline), increased volatility, and sector-specific impacts.
  - **Objective:** Assess portfolio performance under extreme conditions.

**Value at Risk (VaR) and Conditional Value at Risk (CVaR):**
- **Objective:** Calculate and compare VaR and CVaR for different portfolios.
- **Approach:** Use historical simulation and Monte Carlo simulation techniques.

**Stress Testing with Factor Models:**
- **Objective:** Use factor models to stress test portfolios by simulating economic factor movements.
- **Approach:** Implement multi-factor models (e.g., Fama-French) to analyze portfolio sensitivity.

**Liquidity Risk Assessment in Stress Testing:**
- **Objective:** Assess liquidity risk under stressed market conditions.
- **Approach:** Develop models to simulate liquidity shocks, considering bid-ask spreads and trading volumes.
