# 📊 Value at Risk (VaR) & Portfolio Risk Analysis

A comprehensive financial risk analysis project that evaluates portfolio risk using multiple statistical and simulation-based approaches including **Value at Risk (VaR), Monte Carlo Simulation, Bootstrapping, and Backtesting**.

---

## 🚀 Features

- 📉 Value at Risk (VaR) using:
  - Normal Distribution
  - Student’s t-Distribution
  - Historical Method
- 🔁 Monte Carlo Simulation (10,000+ scenarios)
- 📊 Bootstrapping for confidence intervals
- 📈 Portfolio Risk Metrics:
  - Volatility (Standard Deviation)
  - Variance
  - Skewness & Kurtosis
- 📉 Expected Shortfall (CVaR)
- 📊 Rolling VaR (Dynamic risk tracking)
- 🔍 VaR Backtesting (model validation)
- 📉 Drawdown Analysis
- 📊 Portfolio Diversification Analysis
- 📈 Correlation Heatmaps

---

## 🧠 Tech Stack

- **Python**
- **NumPy, Pandas**
- **Matplotlib, Seaborn**
- **SciPy (Statistical Analysis)**
- **yFinance API**
- **pandas-datareader**

---

## 📌 Project Overview

This project analyzes a portfolio of stocks:

- NVIDIA (NVDA)
- Apple (AAPL)
- Google (GOOGL)
- Amazon (AMZN)

It calculates daily returns and evaluates financial risk using multiple statistical techniques to simulate real-world investment scenarios.

---

## 📊 Key Highlights

- Simulated **10,000+ Monte Carlo scenarios** to estimate extreme risk conditions  
- Compared **Normal vs t-distribution VaR**, showing how normal distribution underestimates tail risk  
- Implemented **bootstrapping techniques** to compute confidence intervals for mean and volatility  
- Performed **VaR backtesting** to validate model accuracy against real data  
- Analyzed **portfolio diversification** using correlation matrix and risk reduction  

---

## 📈 Sample Insights

- Stocks like NVDA and AAPL show **positive skewness → higher chances of large gains**  
- GOOGL and AMZN exhibit **negative skewness → higher downside risk**  
- t-distribution captures **fat tails**, providing more realistic risk estimation than normal distribution  
- Diversification reduced portfolio risk significantly compared to individual stock volatility  

---

## ⚙️ Installation

```bash
pip install numpy pandas matplotlib seaborn scipy yfinance pandas-datareader
```

##📊 Use Cases
-📈 Financial Risk Management
-💼 Portfolio Optimization
-🏦 Quantitative Finance Analysis
-📊 Investment Strategy Evaluation
-📈 Future Improvements
-🌐 Deploy as web app (Streamlit)
-📊 Add interactive dashboard
-🤖 Integrate real-time trading signals
-📉 Add deep learning-based risk prediction
-📓 Google Colab Version

-This project was originally developed using Google Colab.

-👉 You can run it directly on:
 Colab

-👨‍💻 Author

-Muhammad Anas
-🔗 GitHub: https://github.com/anas7272

-🔗 LinkedIn: https://linkedin.com/in/muhammadanas
