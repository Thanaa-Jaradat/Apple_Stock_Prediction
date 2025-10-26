# 📈 Apple Stock Analysis

### **Description**
This project performs a comprehensive analysis of Apple Inc. (AAPL) stock prices using Python. It includes historical data visualization, candlestick charts, moving averages, and price prediction using a simple machine learning model.

---

## 🚀 Overview
The project uses historical stock data from Yahoo Finance to provide insights into Apple’s stock trends. It covers multiple aspects of stock analysis:

1. **Line Chart** – Visualizes daily closing prices over the past year.  
2. **Candlestick Chart** – Displays OHLC (Open, High, Low, Close) data for one month for better clarity.  
3. **Moving Averages (MA)** – Calculates 13-day and 60-day moving averages to identify trends.  
4. **Price Prediction** – Uses a Linear Regression model with rolling moving averages to predict future closing prices.

---

## 🧩 Tech Stack
- **Language:** Python  
- **Data Source:** Yahoo Finance (`yfinance`)  
- **Visualization:** Matplotlib, `mplfinance`  
- **Data Processing:** Pandas, NumPy  
- **Machine Learning:** scikit-learn (Linear Regression)

---

## 📁 Project Structure
| File / Section | Description |
|----------------|-------------|
| `Line Chart` | Plots daily closing prices over the past year using Matplotlib |
| `Candlestick Chart` | Shows OHLC candlestick chart for one month using mplfinance |
| `Moving Averages` | Computes and visualizes 13-day and 60-day moving averages on the candlestick chart |
| `Price Prediction` | Uses Linear Regression with date and moving averages to predict future closing prices |

---

## 🌟 Features
- Daily closing price visualization over the past year  
- Candlestick charts for short-term trends  
- Moving averages (13-day & 60-day) to detect stock momentum  
- Linear Regression-based prediction for future stock prices  
- Modular and reusable Python code for stock analysis  

---

## 🧪 Usage
```bash
# 1️⃣ Install dependencies
pip install yfinance mplfinance matplotlib pandas numpy scikit-learn

# 2️⃣ Run the scripts in Python
# - Visualize line chart and candlestick chart
# - Calculate and plot moving averages
# - Predict future closing price
