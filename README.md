# Predicting Google Stock Prices for Enhanced Investment Strategies

## Project Overview

This project aims to create a machine learning pipeline to forecast Google's stock values for the next decade using historical price data. By accurately predicting stock prices, the model seeks to improve investment strategies and help stakeholders make data-driven decisions for portfolio management and transaction planning.

The project frames this task as a regression problem, leveraging advanced deep learning techniques such as Feedforward Neural Networks and Long Short-Term Memory (LSTM) networks to identify patterns and trends in stock price fluctuations.

## Problem Statement

Predicting stock prices is challenging due to the volatility and non-linear nature of financial markets. This project specifically focuses on forecasting Google’s stock prices to enhance investment strategies, enabling investors to manage portfolios with greater accuracy and make timely transactions to maximize returns.

## Data

The dataset includes historical Google stock prices with the following key features:
- **Open Price**: The price at the beginning of the trading day
- **Close Price**: The price at the end of the trading day
- **High Price**: The highest price reached during the trading day
- **Low Price**: The lowest price during the trading day
- **Volume**: The number of shares traded
- **Adjusted Close Price**: The closing price adjusted for splits and dividends

Data is sourced from reliable financial data providers or APIs to ensure accuracy and comprehensiveness.

## Methodology

1. **Data Collection**: Historical Google stock price data is collected, ensuring it includes all critical financial indicators.
2. **Data Preprocessing**: The dataset undergoes preprocessing steps, including cleaning, normalization, and feature selection.
3. **Model Selection**: Both Feedforward Neural Networks and Long Short-Term Memory (LSTM) networks are explored for their effectiveness in time series analysis.
4. **Model Evaluation**: Models are evaluated based on their prediction accuracy and ability to generalize over unseen data.
5. **Forecasting**: The final model is used to generate stock price forecasts for the next decade.

## Usage

To run this project:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/google-stock-price-prediction.git
    ```
2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook:
    Open the notebook in Jupyter Notebook or Jupyter Lab and execute the cells step-by-step to preprocess the data, train the models, and generate forecasts.

## Results

The results include visualizations of stock price trends and forecast accuracy metrics, showcasing the model's capability to capture stock price patterns effectively. The insights gained can aid investors in making informed decisions based on the predicted stock price movements.

## Future Improvements

Potential areas for further development include:
- Experimenting with more complex architectures or hybrid models to enhance prediction accuracy.
- Extending the analysis to other companies for a more comprehensive investment strategy toolkit.
