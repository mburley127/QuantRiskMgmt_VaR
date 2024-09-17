# Quantitative Risk Management - VaR Analysis

This repository contains the implementation of various risk management models in Python, focusing on the **Value at Risk (VaR)** framework, alongside the **Capital Asset Pricing Model (CAPM)** for portfolio performance evaluation.

1. **VaR Model**
- `VaR_analysis`: Contains the implementation of the VaR model. 

This project constructs and analyzes a portfolio using Quantitative Risk Management techniques, primarily through the **Value at Risk (VaR)** framework. VaR is employed to estimate potential portfolio losses during adverse market conditions, providing a measurable risk indicator. The portfolio is built using the **Naive Risk-Parity Portfolio** method, where stock weights are allocated inversely to their volatilities. This ensures that less volatile stocks carry more weight, balancing overall risk. The portfolio consists of 10 diversified stocks from sectors including technology, healthcare, energy, and financials, with 5 years of historical data (2019-2024) sourced from Yahoo Finance.

The analysis calculates the portfolio’s expected returns using the **Capital Asset Pricing Model (CAPM)**, integrating factors such as the risk-free rate, market returns (using the S&P 500 as a benchmark), and the stocks’ beta coefficients. Beta is computed for each stock to understand its sensitivity to market movements, and expected returns are derived accordingly. The portfolio’s risk profile is further examined using the **Variance-Covariance Matrix**, which measures how stock returns move together, allowing for a comprehensive understanding of the portfolio's volatility and overall risk.

Finally, the project evaluates the portfolio’s maximum potential losses over the specified time horizon of 1 day for both **Parametic VaR** and **Variance-Covariance (VCV) VaR**. The results help investors estimate expected returns, assess risk levels, and make more informed decisions based on potential losses under different market scenarios.

2. **results**
- `results`: This directory includes the complete write-up and detailed analysis of the portfolio's risk and performance. Key metrics such as expected returns via CAPM, portfolio volatility, portfolio variance, and Value at Risk (VaR) using both Parametric and Variance-Covariance (VCV) methods are reported. The results provide insights into the portfolio's risk exposure, potential maximum losses, and the effectiveness of risk-parity weighting.

