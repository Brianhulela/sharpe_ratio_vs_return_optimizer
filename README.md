# Sharpe Ratio vs Return: Trading Strategy Optimization with Optuna

This project explores the impact of optimizing a simple trading strategy for two different objectives: **maximum return** vs **maximum Sharpe Ratio**.

Using historical price data for NVIDIA (NVDA), it compares how these two approaches influence performance, trade frequency, and risk-adjusted outcomes. A double moving average crossover (DMAC) strategy is used as the base model, with Optuna handling the hyperparameter optimization.

The study covers:

* Historical price retrieval using `yfinance`
* Strategy logic and return computation
* Custom objective functions for Sharpe Ratio and total return
* Optuna-based tuning of short and long moving average windows
* Visualization of strategy signals and equity curves
* Side-by-side comparison of optimized strategies vs buy-and-hold

The results are evaluated on an out-of-sample test set to assess generalization.

This repository includes all the code and visualizations used in the accompanying article.
