# Quantitative Risk Management - VaR Analysis

This repository contains the implementation of various risk management models in Python, focusing on the **Value at Risk (VaR)** framework, alongside the **Capital Asset Pricing Model (CAPM)** and the **Sharpe Ratio** for portfolio performance evaluation.

## Project Overview
- `VaR_analysis`: Contains the implementation of the VaR model. 

This project constructs and analyzes a portfolio using Quantitative Risk Management techniques, primarily through the **Value at Risk (VaR)** framework. VaR is employed to estimate potential portfolio losses during adverse market conditions, providing a measurable risk indicator. The portfolio is built using the **Risk-Parity Portfolio** method, where stock weights are allocated inversely to their volatilities. This ensures that less volatile stocks carry more weight, balancing overall risk. The portfolio consists of 10 diversified stocks from sectors including technology, healthcare, energy, and financials, with 5 years of historical data (2019-2024) sourced from Yahoo Finance.

The analysis calculates the portfolio’s expected returns using the **Capital Asset Pricing Model (CAPM)**, integrating factors such as the risk-free rate, market returns (using the S&P 500 as a benchmark), and the stocks’ beta coefficients. Beta is computed for each stock to understand its sensitivity to market movements, and expected returns are derived accordingly. The portfolio’s risk profile is further examined using the **Variance-Covariance Matrix**, which measures how stock returns move together, allowing for a comprehensive understanding of the portfolio's volatility and overall risk.

Finally, the project evaluates the portfolio’s performance using the **Sharpe Ratio**, a metric that quantifies risk-adjusted returns. By combining these methodologies—**VaR**, **CAPM**, and the **Sharpe Ratio**—this project offers a robust quantitative risk management framework. The results help investors estimate expected returns, assess risk levels, and make more informed decisions based on potential losses under different market scenarios.

## Results
- `results`: This directory includes the full write-up and detailed analysis of the portfolio's performance. Key metrics such as total returns, mean returns, percentage returns, volatility (standard deviation), and the Sharpe ratio are reported. The results provide a clear comparison of risk-adjusted performance, showing the impact of risk-parity weighting, market sensitivity, and expected returns on portfolio management.

