# Quantitative Investment Strategy

This GitHub repository contains 3 data science projects focused on algorithmic trading strategies. Each project
explores a distinct approach to make data-driven investment decisions within the financial markets. Below is a summary
of each project's motive and key concepts:

## [Project 1: Equal-Weight S&P 500 Index Fund](https://github.com/imsoumya18/quantitative_investment_strategy/blob/main/Project%201%3A%20Equal-Weight%20S%26P%20500%20Index%20Fund/1_equal_weight_s%26p500.ipynb)

**Motive**: The primary objective of this project is to design an Equal-Weight S&P 500 Index Fund. Instead of the
traditional market capitalization-weighted approach used in most index funds, this strategy assigns an equal weight to
all 500 stocks comprising the S&P 500 index.

**Steps**:

- Data preprocessing and cleaning to obtain accurate stock data.
- Creating an equal-weight portfolio by allocating the same amount of funds to each stock.
- Implementing rebalancing strategies to maintain equal weights.

## [Project 2: Quantitative Momentum Investing Strategy](https://github.com/imsoumya18/quantitative_investment_strategy/blob/main/Project%202%3A%20Quantitative%20Momentum%20Investing%20Strategy/2_quantitative_momentum_strategy.ipynb)

**Motive**: This project aims to develop a Quantitative Momentum Investing Strategy based on historical stock price
returns over multiple periods (1 year, 6 months, 3 months, and 1 month). The strategy will identify and invest in stocks
with strong recent performance.

**Key Concepts**:

- Calculating rolling returns for different timeframes to capture momentum.
- Computing percentile scores of returns to rank stocks based on their performance.
- Computing a **High Quality Momentum (HQM) score** as mean of 4 percentiles calculated.

## [Project 3: Quantitative Value Investing Strategy](https://github.com/imsoumya18/quantitative_investment_strategy/blob/main/Project%203%3A%20Quantitative%20Value%20Investing%20Strategy/3_quantitative_value_strategy.ipynb)

**Motive**: This project focuses on building a Quantitative Value Investing Strategy that considers fundamental ratios
such as PE ratio, PB ratio, and price to sales ratio. The goal is to identify undervalued stocks that have the potential
for higher returns.

**Key Concepts**:

- Gathering and cleaning fundamental data for various stocks.
- Calculating valuation ratios to assess the relative attractiveness of each stock.
- Applying filters and thresholds to screen and select undervalued stocks.
- Computing **Robust Value (RV) score** as mean of percentiles of previously calculated percentiles.

Each project is implemented using Python in Jupyter Notebooks, and the necessary datasets are included for
reproducibility. The findings, insights, and performance metrics for each strategy are detailed within their respective
notebooks.

Please feel free to explore the individual notebooks and delve deeper into the strategies to gain a comprehensive
understanding of the data science approaches applied to algorithmic trading. Happy investing! 📈📊

