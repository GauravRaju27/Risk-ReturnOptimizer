# Risk-ReturnOptimizer
Project Overview
This project demonstrates how to optimize a stock portfolio to achieve the highest possible Sharpe ratio, which balances risk (volatility) and returns. Using historical stock data from yfinance, the project calculates annual returns and risks, and optimizes the portfolio weights to maximize the Sharpe ratio.

Key Components
Data Collection: Stock data (e.g., AAPL, TSLA, MSFT) is downloaded using yfinance. Daily returns are calculated and annualized for further analysis.
Optimization: The scipy.optimize.minimize function is used to find the optimal portfolio weights that maximize the Sharpe ratio while considering constraints like no short selling.
Efficient Frontier Visualization: The efficient frontier is plotted to show various risk-return combinations for different portfolio allocations. The optimized portfolio is highlighted on the graph for comparison.

Results
Optimal Portfolio Weights: The optimized weights that achieve the highest Sharpe ratio.
Expected Performance: The optimized portfolio’s expected annual return and risk are calculated and displayed.
Efficient Frontier: A visual representation of possible portfolios with differing risk and return levels, showing how the optimized portfolio compares to others.

This project showcases the application of portfolio theory to optimize investment decisions by balancing risk and return. It provides a practical tool for portfolio allocation using Python.
