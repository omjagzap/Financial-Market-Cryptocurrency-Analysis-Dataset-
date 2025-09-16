# 📊 Financial Market Cryptocurrency Analysis

## 📌 Overview
This project analyzes **Bitcoin (BTC)** and **Ethereum (ETH)** daily prices using the **Yahoo Finance API (yfinance)**.  
We perform **trend analysis, correlation with the stock market (S&P500), and volatility checks**.  
The project demonstrates the use of **Python (Jupyter Notebook)** for data analysis and **Power BI** for interactive dashboards.  

---

## 📂 Dataset
- **Source:** Yahoo Finance via `yfinance` library  
- **Assets:**
  - Bitcoin (BTC-USD)
  - Ethereum (ETH-USD)
  - S&P 500 Index (^GSPC) for market correlation  
- **Data Fields:**
  - Date, Open, High, Low, Close, Adj Close, Volume  
- **Auto-update:** Each time you run the script, fresh data is fetched from Yahoo Finance.  

---

## 🛠 Tools & Libraries
- **Python**:  
  - `yfinance` → to fetch crypto & stock data  
  - `pandas` → data cleaning & manipulation  
  - `numpy` → numerical operations  
  - `matplotlib` → trend & volatility plots  
- **Power BI**:  
  - Interactive dashboard for trends, volatility, and correlation  
  - Filters for Ticker, Date, and metrics  

---

## 🔍 Analysis Performed
1. **Trend Analysis** → BTC & ETH daily closing prices  
2. **Correlation Analysis** → Correlation between BTC, ETH, and S&P500 returns  
3. **Volatility Check** → 30-day rolling volatility of BTC & ETH  
4. **Trading Volume Analysis** → Spikes and market activity  

---

## 📈 Graphs & Visualizations (Python)
- Line Chart → BTC vs ETH closing price trends  
- Scatter Plot → BTC vs ETH daily returns (correlation check)  
- Volatility Line → Rolling 30-day volatility comparison  
- Bar Chart → Daily trading volumes  

---

## 📝 Steps to Run (Jupyter Notebook)
1. Install dependencies:
   ```bash
   pip install yfinance pandas numpy matplotlib
