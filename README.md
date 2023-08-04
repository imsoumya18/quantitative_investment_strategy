# Data Science Projects on Algorithmic Trading

![Algorithmic Trading](images/algorithmic_trading.jpg)

This GitHub repository contains three data science projects focused on algorithmic trading strategies. Each project explores a distinct approach to make data-driven investment decisions within the financial markets. Below is a summary of each project's motive and key concepts:

## Project 1: Equal-Weight S&P 500 Index Fund

**Motive**: The primary objective of this project is to design an Equal-Weight S&P 500 Index Fund. Instead of the traditional market capitalization-weighted approach used in most index funds, this strategy assigns an equal weight to all 500 stocks comprising the S&P 500 index.

![Equal-Weight S&P 500](images/equal_weight_sp500.jpg)

**Key Concepts**:
- Data preprocessing and cleaning to obtain accurate stock data.
- Creating an equal-weight portfolio by allocating the same amount of funds to each stock.
- Implementing rebalancing strategies to maintain equal weights over time.
- Evaluating the performance of the Equal-Weight S&P 500 Index Fund against the standard market-cap weighted S&P 500.

## Project 2: Quantitative Momentum Investing Strategy

**Motive**: This project aims to develop a Quantitative Momentum Investing Strategy based on historical stock price returns over multiple periods (1 year, 6 months, 3 months, and 1 month). The strategy will identify and invest in stocks with strong recent performance.

![Quantitative Momentum Investing](images/momentum_investing.jpg)

**Key Concepts**:
- Calculating rolling returns for different timeframes to capture momentum.
- Computing percentile scores of returns to rank stocks based on their performance.
- Constructing a portfolio of top-performing stocks according to the percentile ranking.
- Analyzing and comparing the returns and risk of the Quantitative Momentum Investing Strategy against a benchmark.

## Project 3: Quantitative Value Investing Strategy

**Motive**: This project focuses on building a Quantitative Value Investing Strategy that considers fundamental ratios such as PE ratio, PB ratio, and price to sales ratio. The goal is to identify undervalued stocks that have the potential for higher returns.

![Quantitative Value Investing](images/value_investing.jpg)

**Key Concepts**:
- Gathering and cleaning fundamental data for various stocks.
- Calculating valuation ratios to assess the relative attractiveness of each stock.
- Applying filters and thresholds to screen and select undervalued stocks.
- Constructing a value portfolio based on the selected stocks and monitoring its performance.

Each project is implemented using Python in Jupyter Notebooks, and the necessary datasets are included for reproducibility. The findings, insights, and performance metrics for each strategy are detailed within their respective notebooks.

Please feel free to explore the individual notebooks and delve deeper into the strategies to gain a comprehensive understanding of the data science approaches applied to algorithmic trading. Happy investing! 📈📊

![Happy Investing](images/happy_investing.jpg)
