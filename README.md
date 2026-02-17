# portfolio-optimization-markowitz
Implementation of Modern Portfolio Theory (Markowitz) in Python with Monte Carlo simulation, efficient frontier construction, and S&amp;P 500 benchmark comparison.

# Portfolio Optimization using Markowitz Model

## Project Overview

This project implements Modern Portfolio Theory (MPT) using the Markowitz mean-variance framework to optimize a portfolio composed of:

- AAPL
- MSFT
- GOOG
- TSLA

The objective is to:
- Maximize Sharpe Ratio
- Minimize Volatility
- Construct the Efficient Frontier
- Compare results to the S&P 500 benchmark

---

## Methodology

###  Data Collection
Historical daily prices were downloaded using `yfinance` from 2018 to 2025.

###  Key Metrics Computed
- Daily returns
- Annualized returns
- Annualized volatility
- Covariance matrix

###  Monte Carlo Simulation
5000 random portfolios were generated to:
- Explore different weight combinations
- Estimate return, volatility, and Sharpe ratio

###  Optimization
- Maximum Sharpe Portfolio
- Minimum Volatility Portfolio
- Efficient Frontier construction

###  Benchmark Comparison
Performance was compared against the S&P 500 index.

---

## Key Findings

- Diversification improves risk-adjusted returns.
- The Maximum Sharpe portfolio provides superior risk-adjusted performance.
- The Minimum Volatility portfolio suits conservative investors.
- The Efficient Frontier confirms theoretical expectations from Markowitz theory.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance

---

##  How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
