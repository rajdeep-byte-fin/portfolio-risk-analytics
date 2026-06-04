# Portfolio Optimization & Risk Analytics Platform

Mean-variance portfolio optimization on NIFTY 50 stocks using Monte Carlo simulation and quantitative risk metrics.

## Results
- **Return:** 14.3% (annualized)
- **Volatility:** 22.7%
- **Sharpe Ratio:** 0.36
- **95% VaR:** −1.94% | **CVaR:** −3.14%
- **March 2020 Stress Test:** ~−50% drawdown

## What it does
- Pulls 5 years of historical data for 5 NIFTY stocks using `yfinance`
- Runs 10,000+ Monte Carlo simulations to find the optimal portfolio weights
- Maximizes Sharpe ratio using `SciPy` optimization
- Measures downside risk via Value-at-Risk and Conditional VaR
- Stress tests the portfolio against the COVID crash (March 2020)

## Tech Stack
`Python` `NumPy` `Pandas` `SciPy` `yfinance` `Matplotlib` `Google Colab`

## Run it
Open directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rajdeep-byte-fin/portfolio-risk-analytics/blob/main/portfolio_optimization.ipynb)# portfolio-risk-analytics
Portfolio Optimization
