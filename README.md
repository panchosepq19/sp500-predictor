# sp500-predictor

This project uses a Random Forest Classifier to predict whether the S&P 500 will go up or down. The model is trained on data from Yahoo Finance and uses a variety of predictors, including closing price, volume, open, high, low, and rolling averages.

## Getting Started

To run this project, you will need to have the following libraries installed:

* yfinance
* scikit-learn
* pandas

You can install these libraries using pip:

pip install yfinance scikit-learn pandas

Once you have installed the necessary libraries, you can download the Jupyter Notebook from this repository and run it in Google Colab.

## Backtesting

The model is backtested using a rolling window approach. The model is trained on the first 10 years of data and then tested on the 11th year. This process is repeated for each subsequent year.

## Results

The model achieves a precision of 67.95%. This means that when the model predicts that the market will go up, it is correct 67.95% of the time.

## Future Work

Possible future work includes:

* Adding more predictors
* Tuning the hyperparameters of the model
* Using a different machine learning model
