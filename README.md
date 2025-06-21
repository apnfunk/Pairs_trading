# Pairs Trading Strategy using Statistical Arbitrage

##  Project Overview
This project implements a **Pairs Trading** strategy — a market-neutral approach that profits from relative price movements between two cointegrated stocks. It uses statistical tests to identify suitable pairs and applies a mean-reversion trading logic to generate buy/sell signals.

> Inspired by quantitative finance principles, this strategy focuses on **cointegration** over mere correlation to ensure robustness.

---

##  Key Features

- Selection of asset pairs using **cointegration tests (Engle-Granger)**
- Construction of a **mean-reverting spread**
- **Z-score-based trading signals**
-  Market-neutral exposure (long one asset, short the other)
-  Backtest logic using historical price data
-  Ready for extension with **transaction costs** and **intraday strategy**

---

## Statistical Concepts Used

- Correlation vs Cointegration
- Engle-Granger Test
- Mean Reversion & Z-score normalization
- Strategy performance analysis



