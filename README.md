# coffee-futures-monte-carlo-simulation
#  Coffee Futures Price Forecasting using Monte Carlo Simulation

A quantitative finance project that forecasts possible future coffee futures prices using **Monte Carlo Simulation** based on historical market data.

The project applies statistical modeling and risk analysis techniques commonly used in financial markets to simulate multiple future price paths and evaluate uncertainty in commodity price movements.

---

##  Project Overview

Financial markets are inherently uncertain, making it impossible to predict future prices with certainty.

Instead of forecasting a single price, Monte Carlo Simulation generates thousands of possible future price paths using historical market behaviour.

This project demonstrates how historical returns and volatility can be used to estimate a probability distribution of future coffee futures prices while also measuring investment risk through multiple financial metrics.

---

##  Objectives

- Analyze historical coffee futures prices
- Calculate daily returns
- Estimate average return (μ)
- Estimate volatility (σ)
- Compute financial risk metrics
- Simulate future coffee prices using Monte Carlo Simulation
- Visualize multiple possible future price paths
- Estimate confidence intervals for future prices

---

##  Features

- Historical Coffee Futures Data Analysis
- Daily Return Calculation
- Volatility Estimation
- Sharpe Ratio Calculation
- Maximum Drawdown Analysis
- Value at Risk (VaR)
- Monte Carlo Price Simulation
- 95% Confidence Interval Estimation
- Data Visualization using Matplotlib

---

##  Methodology

The project follows the workflow below:

```text
Historical Market Data
          │
          ▼
 Data Cleaning & Preparation
          │
          ▼
 Daily Return Calculation
          │
          ▼
 Mean (μ) & Volatility (σ)
          │
          ▼
 Risk Metrics
          │
          ▼
 Monte Carlo Simulation
          │
          ▼
 Future Price Distribution
          │
          ▼
 Confidence Interval Analysis
```

---

##  Monte Carlo Simulation

Monte Carlo Simulation estimates future prices by repeatedly generating random daily returns from a normal distribution:

\[
R \sim N(\mu,\sigma)
\]

where:

- **μ** = Historical Mean Daily Return
- **σ** = Historical Standard Deviation (Volatility)

Each simulated return is compounded to generate a possible future price path.

The project simulates **1000 future price paths** across **252 trading days**.

---

##  Risk Metrics Used

### Sharpe Ratio

Measures return generated per unit of risk.

### Maximum Drawdown

Measures the largest peak-to-trough decline during the investment period.

### Value at Risk (VaR)

Estimates the maximum expected loss at a specified confidence level under normal market conditions.

---

##  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- yfinance

---

##  Project Structure

```
coffee-futures-monte-carlo-simulation/
│
├── Coffee_Futures_Monte_Carlo.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

##  Sample Output

The notebook includes visualizations such as:

- Historical Coffee Futures Prices
- Daily Returns Distribution
- Monte Carlo Simulation Paths
- Confidence Interval Analysis

---

##  Future Improvements

- Geometric Brownian Motion (GBM)
- Correlated Asset Simulation
- Interactive Dashboard using Streamlit
- Scenario Analysis
- Machine Learning-based Forecast Comparison

---

##  Key Concepts

- Monte Carlo Simulation
- Financial Risk Analysis
- Quantitative Finance
- Probability Theory
- Statistical Modeling
- Commodity Price Forecasting
- Data Analysis

---


##  Author

**Suhani Chavda **



---

## ⭐ If you found this project useful, consider giving it a star!
