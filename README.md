# Combining Machine Learning and Deep Learning for Real-Time Cryptocurrency Price Prediction

## Introduction
This repository contains the code and resources for a class project on Combining Machine Learning and Deep Learning for Real-Time Cryptocurrency Price Prediction. The project explores the performance of Linear Regression, ARIMA, Recurrent Neural Networks (RNN), Gated Recurrent Units (GRU), Long Short-Term Memory (LSTM) networks, Holt-Winters, Gradient Boosting Regression, Bagging Model, PatchTST, and LightGBM in forecasting the prices of Bitcoin, Ethereum, and Binance.

## Dataset
The dataset used in this project is collected from �, containing daily data for Bitcoin, Ethereum, and Dogecoin from 01/03/2019 to 17/02/2024. The dataset includes features such as Date, Open, High, Low, Close, Adj Close, Volume.

## Feature Engineering
To improve the predictive performance of the models, the project incorporates technical indicators as features. These indicators, such as moving averages and momentum indicators, provide insights into market sentiment and trends, aiding in the prediction of price movements.

## Models
The following models are implemented and evaluated in this project:

- Linear Regression
- ARIMA
- Holt-Winters
- Recurrent Neural Networks (RNN)
- Gated Recurrent Units (GRU)
- Long Short-Term Memory (LSTM)
- Gradient Boosting Regression
- LightGBM
- Bagging Model - Random Forest
- Patch TST

## Evaluation
The models are evaluated using various performance metrics, such as Root Mean Squared Error (RMSE), Mean Absolute Percent Error (MAPE), and Mean Squared Error (MSE). Three different train-test split ratios are used for each model: 70:30, 80:20, and 60:40. The results are compared to assess the strengths and weaknesses of each model in accurately predicting cryptocurrency prices.

## Division of Work
| Member | Responsibilities |
| --- | --- |
| Le Tuan Dat | Implemented GRU and Gradient Boosting Regression models. Contributed to project documentation.|
| Tran Xuan Bang | Implemented Linear Regression and Bagging models. Contributed to researching related work and project documentation.|
| Hoang Gia Loc | Implemented ARIMA and PatchTST models. Contributed to project documentation.|
| Vo Hong Kim Anh | Implemented LSTM and LightGBM models. Contributed to researching related work and project documentation.|
| Vu Thanh Doan | Implemented RNN and Holt-Winters models. Contributed to project documentation.|


## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments
We would like to thank our instructor and the University of Information Technology for providing the resources and support for this class project.
