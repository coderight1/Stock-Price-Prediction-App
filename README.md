# Stock Price Prediction App

This project is a **Stock Price Prediction App** built using Python and Streamlit. It fetches stock data from Yahoo Finance and uses the Prophet library to predict stock prices for the next 1 to 4 years.

## Features
- **Interactive UI:** Select a stock and specify prediction years.
- **Data Visualization:** Line charts for stock prices and forecasted trends.
- **Data Source:** Uses Yahoo Finance for historical stock prices.
- **Forecasting:** Implements Facebook Prophet for accurate predictions.

## Libraries Used
- Streamlit
- Yahoo Finance (`yfinance`)
- Prophet
- Plotly

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/coderight1/Stock-Price-Prediction-App.git
   cd Stock-Price-Prediction-App

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt

3. Run the app:
    ```bash
    streamlit run main.py


## Usage

1. Select a stock ticker from the dropdown menu.
2. Choose the number of years for prediction (1 to 4 years).
3. View the forecasted stock prices and interactive charts.

## Contributing
Feel free to fork this repository, make your changes, and create a pull request. Contributions are welcome!
