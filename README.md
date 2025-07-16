# Stock Market Prediction with LSTM

This project explores the use of deep learning techniques for time series forecasting in the stock market. It focuses on analyzing and predicting stock prices of major technology companies using historical data and Long Short-Term Memory (LSTM) networks.

## Objective

To develop an end-to-end pipeline that:
- Collects and visualizes historical stock data
- Performs risk and return analysis
- Trains an LSTM model to predict future stock prices

This project demonstrates my ability to work with sequential financial data and build predictive models using deep learning.

## Dataset

Historical stock price data was obtained using the `yfinance` library. The stocks analyzed include:
- Apple (AAPL)
- Amazon (AMZN)
- Google (GOOGL)
- Microsoft (MSFT)

The data includes:
- `Open`, `High`, `Low`, `Close`, `Adj Close`, and `Volume`
- Daily records spanning multiple years

## Tools & Libraries Used

- Python
- yfinance for collecting stock market data
- NumPy, pandas for data manipulation
- matplotlib, seaborn, plotly for visualization
- scikit-learn for scaling and preprocessing
- TensorFlow/Keras for building the LSTM model

## Key Analyses

### Exploratory Analysis
- Visualized stock price trends over time
- Compared stock performance
- Calculated and plotted daily returns
- Analyzed risk using volatility and return distributions

### LSTM Modeling
- Built and trained a univariate LSTM model to predict future prices
- Normalized the data and created time-windowed sequences
- Evaluated model performance using RMSE
- Plotted predicted vs actual prices to assess model accuracy

## Outcomes

- Demonstrated the feasibility of using LSTMs for short-term stock price forecasting
- Visualized how deep learning models learn from temporal financial patterns
- Gained insights into the tradeoffs and challenges of time series modeling in finance

## Limitations & Future Work

- Current model uses only closing prices; incorporating technical indicators and multivariate features could improve accuracy
- Further hyperparameter tuning and use of bidirectional or stacked LSTMs could enhance performance
- Evaluation metrics could be expanded to include directional accuracy and backtesting with trading strategies
