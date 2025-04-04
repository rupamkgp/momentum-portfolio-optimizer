# momentum-portfolio-optimizer
📊 Momentum-Based Portfolio Optimization &amp; Backtesting  This project implements a quantitative investment strategy using Markowitz Mean-Variance Optimization to maximize the Sharpe Ratio. The strategy selects top 5 momentum stocks every quarter and rebalances the portfolio based on historical price data from Yahoo Finance. 



# 📊 Portfolio Optimization & Backtesting with Python

This project demonstrates how to construct and backtest an optimized stock portfolio using historical data from Yahoo Finance. The strategy selects the top-performing stocks by momentum and allocates capital using **Markowitz Mean-Variance Optimization** to maximize the Sharpe Ratio.

---

## 🚀 Features

- ✅ **Quarterly Rebalancing** with top 5 momentum stocks
- ✅ **Markowitz Optimization** (Max Sharpe Ratio Portfolio)
- ✅ **Realistic Trading Costs** (0.1% per transaction)
- ✅ **Performance Metrics**: Total Return, Sharpe Ratio, Max Drawdown
- ✅ **Clean Visualization** of Cumulative Returns (Year-wise)

---


## 📁 Project Structure

```bash
portfolio-optimizer/
│
├── portfolio_optimization.py       # Main Python script
├── requirements.txt                # Required Python libraries
├── outputs/
│   └── cumulative_returns_plot.png # Visualization of portfolio performance
└── README.md                       # Project overview and documentation
```

## 📈 Strategy Overview

1. **Data Collection**: Pulls 2 years of historical data for 10 major stocks.
2. **Stock Selection**: Ranks stocks based on 6-month momentum.
3. **Optimization**: Calculates optimal weights using Markowitz model.
4. **Backtesting**: Rebalances portfolio quarterly and tracks performance.
5. **Evaluation**: Computes Sharpe ratio, total return, and max drawdown.

---





## 🛠️ Tools & Libraries

- `Python`
- `pandas`
- `numpy`
- `matplotlib`
- `yfinance`

---




## 📄 Documentation

- [📘 Portfolio Strategy Report (PDF)](docs/Portfolio Construction Report.pdf)






## 📊 Output Example

![Cumulative Returns Plot](![Screenshot 2025-04-04 061132](https://github.com/user-attachments/assets/8713f443-2f8a-42ce-908b-ab4974fd3338)
.png)

---



## 📂 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/portfolio-optimization.git
cd portfolio-optimization

# Install dependencies
pip install -r requirements.txt

# Run the script
python portfolio_optimization.py

