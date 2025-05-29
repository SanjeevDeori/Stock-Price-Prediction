# 📊 Stock Price Prediction Web App

A 🌐 **Streamlit web application** that predicts future stock prices using historical data and an **LSTM neural network**. The app fetches real-time stock data using **Yahoo Finance (`yfinance`)**, processes it with technical indicators, trains an LSTM model, and visualizes predicted stock prices for the next **10 days**.

---

## ✨ Features

✅ Fetches **5 years** of historical stock data dynamically via `yfinance`  
✅ Computes multiple **technical indicators**:  
  • SMA, EMA, RSI, Bollinger Bands  
  • Momentum, Volatility, Log & Daily Returns  
✅ Scales and prepares data for **LSTM time series forecasting**  
✅ Trains a **two-layer LSTM neural network**  
✅ Predicts and visualizes stock prices for the **next 10 days**  
✅ **Interactive Streamlit interface** for easy input and visualization  
✅ Model **caching** to avoid retraining for repeated stock queries

---
## 🧰 Technologies Used

- 🐍 Python  
- 📈 Streamlit  
- 🧠 TensorFlow / Keras  
- 💹 yfinance  
- 🧮 pandas, numpy  
- 📊 scikit-learn  
- 📉 plotly  

---

## ⚙️ Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/SanjeevDeori/Stock-Price-Prediction.git
   cd Stock-Price-Prediction
2. Create and activate a virtual environment(optional):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```
3. Install dependencies
   ```bash
   
   pip install -r requirements.txt
   
## 🚀 Usage
Run the Streamlit app locally by executing:
```bash
   streamlit run app.py
```
(or replace app.py with your script filename)

Enter a stock ticker symbol (e.g., AAPL, MSFT, TSLA) in the input box.

Click Train and Predict to train the model and view 10-day price predictions.

The app displays the latest closing price, model evaluation metrics, predicted prices in a table, and an interactive plot.

## 📄 License

This project is licensed under the **MIT License**.

## 📬 Contact

For any questions or suggestions, reach out to:

- **GitHub**: [@SanjeevDeori](https://github.com/SanjeevDeori)  
- **Email**: sanjeevdeori743.jams@gmail.com


Happy Trading! 📈🚀

