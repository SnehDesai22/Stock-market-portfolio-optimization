# Stock Market Portfolio Optimization

This project demonstrates **portfolio optimization** techniques to identify the best asset allocation for maximizing returns while minimizing risk, based on historical stock market data.

## 📌 Project Overview
The notebook implements **Modern Portfolio Theory (MPT)** to:
- Calculate expected returns and risk (volatility) for different portfolios.
- Determine the **Maximum Sharpe Ratio portfolio** for optimal risk-adjusted returns.
- Visualize the **Efficient Frontier**.

## 📊 Techniques Used
- **Data Retrieval**: Historical stock price data.
- **Data Processing**: Return calculation, covariance matrix computation.
- **Optimization**: Random portfolio generation and Sharpe Ratio maximization.
- **Visualization**: Scatter plots for portfolio return vs volatility.

## ⚙️ Requirements
Install dependencies:
```bash
pip install pandas numpy matplotlib yfinance
```

## 🚀 How to Run
1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Stock_market_portfolio_optimization.ipynb
   ```
2. Run all cells to:
   - Load stock data
   - Generate portfolios
   - Identify the optimal allocation

## 📈 Results
- Outputs the portfolio weights with **highest Sharpe Ratio**.
- Shows annualized returns, volatility, and Sharpe Ratio.
- Visualizes Efficient Frontier for better decision-making.

## 📂 Files
- `Stock_market_portfolio_optimization.ipynb` → Main Jupyter Notebook
- `README.md` → This documentation

---
💡 **Tip**: Modify `unique_tickers` in the notebook to test different stock combinations.
