Markdown
# Market Risk Analysis and Monte Carlo Simulation for the S&P 500

This tool retrieves current stock market data to estimate risk metrics and generate probabilistic forecasts.

## 🚀  Project Features
* **Automated data retrieval: Integration with the yfinance API to obtain historical S&P 500 index quotes.
* **Value at Risk (VaR) calculation: Determination of historical VaR at a 99% confidence level, representing the maximum expected one-day loss.
* **Descriptive statistics: Calculation of average daily return and standard deviation (volatility).
* **Monte Carlo simulation: Generation of 5,000 independent price scenarios for the index over a 30-day horizon using Geometric Brownian Motion (GBM).
* **Data visualization: Generation of clear charts showing return distributions and simulated price trajectories using the matplotlib and seaborn libraries.
