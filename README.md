# Predicting Bulldozer Sale Prices with Machine Learning
This project demonstrates an end-to-end machine learning workflow for predicting the sale prices of bulldozers based on their historical sales data and technical characteristics. Using information from past transactions, the model aims to estimate the future sale price of a bulldozer given its attributes.
Inputs include features such as the year of manufacture, base model, model series, sale location (U.S. state), drive system, and other technical specifications.
Output is the predicted bulldozer sale price in U.S. dollars.
Because the target variable is a continuous numeric value, this task is formulated as a regression problem. Additionally, since predictions are made for future sales based on historical data, the problem also incorporates elements of time-series forecasting.
The dataset and evaluation metric used in this project—Root Mean Squared Logarithmic Error (RMSLE)—are taken from the Kaggle Bluebook for Bulldozers competition.
