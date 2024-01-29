# Pair Trading Strategy

## Overview

Pair trading is a market-neutral strategy widely used in quantitative finance. It involves matching a long position with a short position in two highly correlated stocks. The core idea is to capitalize on the mean-reverting nature of the price ratio or spread between the two stocks.

This project implements a basic pair trading strategy using Python, demonstrating the concepts of statistical arbitrage and mean reversion in financial markets.

## Features

- **Data Fetching:** Utilizes `yfinance` to fetch historical stock data.
- **Spread Analysis:** Calculates the spread between two correlated stocks.
- **Z-Score Normalization:** Employs Z-Score for identifying significant deviations in the spread.
- **Dynamic Time Warping (DTW):** Optionally includes DTW to measure the similarity in the price movements of the stocks.
- **Trading Signals:** Generates buy and sell signals based on predefined thresholds.
- **Backtesting:** Simple backtesting logic to evaluate the strategy's performance.
- **Visualization:** Plots to visualize stock prices, spread, Z-Score, and trading signals.

![image](https://github.com/chenenen13/Pair-trading/assets/122288399/6e42c54f-7dc0-4be5-a441-6ed0e1a1fa27)
