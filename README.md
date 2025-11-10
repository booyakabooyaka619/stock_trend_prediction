
# Stock Trend Prediction

This project, Stock Trend Prediction using LSTM, aims to forecast the movement of stock prices based on historical data. It combines data collection, machine learning, and visualization in an interactive web app built with Streamlit. The system retrieves real-time stock data from Yahoo Finance, analyzes past trends, and uses a Long Short-Term Memory (LSTM) neural network to predict how the stock price will move in the near future. Users can input any stock ticker (like AAPL, TSLA, or MSFT) and view closing price charts, moving averages, and a comparison between the actual and predicted prices.

## Tech Stack
**Frontend (Client):**

- Streamlit – For building the interactive web interface
- Matplotlib – For plotting stock trends


**Backend (Server):**

- Python – Core programming language
- TensorFlow / Keras – For building and running the LSTM deep learning model
- Scikit-learn – For data scaling and preprocessing
- Pandas & NumPy – For data manipulation and numerical operations

**Data Source:**

- Yahoo Finance (via yfinance API) – To fetch historical stock data

**Model:**

- LSTM (Long Short-Term Memory) neural network for time-series prediction

**Deployment:**

- Streamlit Cloud or Localhost – For hosting and running the web app


## Deployment

To deploy this project run the below command in your terminal

```bash
  streamlit run app.py
```


## Screenshots

![App Screenshot](https://github.com/booyakabooyaka619/stock_trend_prediction/blob/main/Screenshot%20(154).png)

![App Screenshot](https://github.com/booyakabooyaka619/stock_trend_prediction/blob/main/Screenshot%20(155).png)

![App Screenshot](https://github.com/booyakabooyaka619/stock_trend_prediction/blob/main/Screenshot%20(156).png)

![App Screenshot](https://github.com/booyakabooyaka619/stock_trend_prediction/blob/main/Screenshot%20(157).png)

![App Screenshot](https://github.com/booyakabooyaka619/stock_trend_prediction/blob/main/Screenshot%20(158).png)

