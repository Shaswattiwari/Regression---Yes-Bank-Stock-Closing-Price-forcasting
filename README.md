## Stock Price Forecasting with LSTM

This Python script implements a stock price forecasting model using Long Short-Term Memory (LSTM) neural networks. The model takes historical stock price data as input and predicts future price movements. Below is an overview of the functionality and usage of the code.

## Overview

The script performs the following main tasks:

#### Data Loading: 
Loads historical stock price data from a CSV file. 
#### Data Preprocessing: 
Preprocesses the data by handling missing values, creating lag features, and scaling the data. Time Series
 #### Data Preparation:
Prepares the time series data by splitting it into input features and target variables with a specified number of time steps. 
#### Model Building and Training: 
Constructs an LSTM model using the Keras Sequential API, compiles it with the Adam optimizer, and trains it on the prepared time series data. 
#### Forecasting: 
Uses the trained model to forecast future stock prices for a specified number of days. 
#### Visualization: 
Plots historical stock prices along with forecasted prices for visual comparison.

## Dependencies The following Python libraries are required to run the script:

pandas | numpy | matplotlib | tensorflow | keras |  scikit-learn

#### These dependencies can be installed via pip using the following command:

```
pip install pandas numpy matplotlib tensorflow scikit-learn
```

## Usage To use the script, follow these steps:

Ensure that you have installed all required dependencies. Prepare your historical stock price data in CSV format with columns for date, open, high, low, close, adjusted close, and volume. Update the data_file variable in the script to point to the location of your CSV file. Adjust any other parameters such as lag periods, time steps, and forecast horizon as needed. Run the script using a Python interpreter:
```
stock_forecasting.py
```

