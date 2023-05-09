# Airbus Stock Analysis and Prediction

The aim of this project is to analyse historical stock data of Airbus SE and build a predictive model to forecast future stock prices. The project uses Python and various data analysis and machine learning libraries to process and analyze the data.

### Data Sources

The historical stock data is obtained from the Yahoo Finance website in the form of a CSV file. The data includes daily stock prices of Airbus SE from 17th September 2001 to the present day.

### Data Analysis

The data needs to be cleaned and preprocessed prior to analysis for a smooth analysis. This preprocessing and cleaning includes converting the "Date" column into a datetime datatype and checking for any null values and outliers in the data and dropping those values. After the preprocessing, the analysis includes:

1. Visualizing the daily stock prices over time
2. Calculating daily returns and visualizing them over time
3. Calculating moving averages and visualizing them over time

### Prediction Model

The project builds a predictive model using the LSTM deep learning algorithm. The model is trained on historical data and tested on a holdout dataset. The performance of the model is evaluated using various metrics such as mean squared error (MSE), mean absolute error (MAE), and R-squared.

### Repository Structure

- **notebook**: contains Jupyter notebook for data preprocessing, analysis, and modeling
- **requirements.txt**: contains a list of Python packages required to run the code

### Getting Started

To run this project on your local machine, follow these steps:

- Clone this repository to your local machine
- Open the '.ipynb' notebook files in your Google Colab and simply run the code

Alternatively:

- Clone this repository to your local machine
- Install the required packages using **pip install** command in *cmd* for the libraries found in the requirements.txt file
- Open the Jupyter notebooks in the **notebooks** directory to run the code

### Conclusion

This project provides a comprehensive analysis of the historical stock data of Airbus SE and builds a predictive model to forecast future stock prices. The project can be extended to analyze other stocks and make investment decisions based on the predictions.
