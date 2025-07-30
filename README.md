# Bitcoin Signal Prediction

A project for building, training, and evaluating machine learning models to predict Bitcoin trading signals using Binance API data.

## Story
[Click Here!](https://medium.com/@BadLuckZ/building-crypto-trading-signal-models-from-api-to-machine-learning-models-f374cda06eda) (Thai Version)

## Features

- Collects historical price data from Binance API
- Calculates technical indicators such as MA, RSI, MACD, and Bollinger Bands
- Trains multiple ML models such as LR, RF, XGB, KNN, and SVM
- Compares performances, picking the best model, and simulates trading strategies

## Setup

1. Clone this repository.

2. Install:
   ```
   pip install python-dotenv python-binance pandas numpy matplotlib scikit-learn xgboost imbalanced-learn
   ```
3. Create a `.env` file with your Binance API credentials:
   ```
   API_KEY=your_api_key
   API_SECRET=your_api_secret
   ```

## Usage

- Run the notebook `main.ipynb` for step-by-step instructions.
- Follow the notebook cells to collect data, train models, and simulate trading.
- To simulate trading, call the function in a code cell:
  ```python
  simulate("ETHBTC")
  ```
  Or leave it blank to select a symbol interactively:
  ```python
  simulate()
  ```

## References

- [Binance API Documentation](https://developers.binance.com/docs/binance-spot-api-docs)

## Disclaimer

This project is for educational purposes only. No financial advice.
