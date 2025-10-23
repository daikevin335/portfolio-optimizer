# Portfolio Optimizer

# Portfolio Optimizer — Markowitz Mean-Variance & Sharpe Ratio Analysis

A personal side project I built to explore **Modern Portfolio Theory** and learn how to translate financial mathematics into real, working code.  
This notebook uses Python to construct and optimize a portfolio based on the **Markowitz Mean-Variance Model**, while also integrating **Sharpe Ratio maximization** to identify the best risk-adjusted allocation.

---

##  Project Overview

This project combines both **risk minimization** (Markowitz Efficient Frontier) and **return optimization** (Sharpe Ratio maximization) in a single analysis workflow.

### Key Features
- **Data Collection:** Automatically pulls 5 years of price data from Yahoo Finance  
- **Risk-Free Rate Integration:** Fetches current 10-Year Treasury yield from FRED API  
- **Return & Covariance Calculation:** Computes annualized expected returns (μ) and covariance matrix (Σ)  
- **Markowitz Optimization:** Generates Efficient Frontier portfolios minimizing variance for a given return  
- **Sharpe Ratio Maximization:** Finds the tangency portfolio with the highest risk-adjusted return  
- **Visualization:** Plots Efficient Frontier, tangency portfolio, and weight allocations


## Tech Stack

| Library | Purpose |
|----------|----------|
| `numpy` | Numerical computation |
| `pandas` | Data manipulation |
| `yfinance` | Market data retrieval |
| `scipy.optimize` | Portfolio optimization (SLSQP) |
| `matplotlib` | Visualization (Efficient Frontier plots) |
| `fredapi` | Fetching real-time risk-free rate |

---

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/daikevin335/portfolio-optimizer.git
cd portfolio-optimizer
