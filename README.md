# Stock Price Prediction Using RNN

## Project Overview
This project aims to predict the price of S&P500 using RNN algorithms.
However, using models to predict stock price is somehow not very realistic since it is also influenced by many other factors besides the past price. Hence, this project focuses on the building of algorithm instead of aiming to earn money by predicting the future stock prices.

## Dataset
The datasets is downloaded via yahoo finance library.
Download the yfinance module.
```bash
pip install yfinance
```
The dataset includes the following features:
Close, Open, Low, Open and Volume of the daily stock price.

## Installation
To run this project, you need to have Python installed along with the following libraries:
```bash
yfinance==0.2.18
pandas==1.5.3
google-colab==1.0.0
numpy==1.24.3
matplotlib==3.7.1
scikit-learn==1.3.0
tensorflow==2.12.0
pandas-ta==0.3.14b0
```
You can install the required packages using the following command after
[cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

```bash
pip install -r requirements.txt
```

## Directory Tree
RNN-stock-price-prediction/
│
├── stockprice_prediction.ipynb # Jupyter notebook containing the analysis and model training(orginally in google colab)
├── sp500_data_two_year.csv # Titanic dataset
├── requirements.txt # List of required Python packages
└── README.md # Project documentation

## Author
Jasper Lung
linkedin.com/in/jasper-lung-95aa29242
