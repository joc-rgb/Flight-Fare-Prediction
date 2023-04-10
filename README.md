# Flight Fare Prediction using XGBoost, Linear Regression, and Random Forest Tree

This project aims to predict the fare of flight tickets based on various features such as departure time, arrival time, number of stops, etc. Three machine learning models were used in this project - XGBoost, Linear Regression, and Random Forest Tree. The performance of these models was compared to determine which one gave the best results.

## Dataset

The dataset used in this project is available on Kaggle - [https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh](https://www.kaggle.com/datasets/jillanisofttech/flight-price-prediction-dataset). It contains information on flight tickets from various airlines traveling between different cities in India. The dataset includes features such as the departure time, arrival time, duration of the flight, number of stops, airline, and source and destination cities.

## Model Building

Three machine learning models were used in this project - XGBoost, Linear Regression, and Random Forest Tree. The data was preprocessed and split into training and testing sets. The models were trained on the training data and evaluated on the testing data. The performance of each model was compared using various evaluation metrics such as RMSE, MAE, R-squared and adjusted R-squared.

## Results

| Model | MAE | MSE | RMSE | R2 | Adjusted R2
| :--- | :--- | :--- | :--- | :--- | :--- |
| XGBoost   | 608.284 | 1121491.26 |1100.6776 | 0.9254 | 0.9253
|Random Forest Regression | 622.000 | 1351458.41 | 1162.52 | 0.9167 | 0.9167
|Linear Regression | 1648.21 | 4887046.34 | 2210.6665 | 0.6989 | 0.6987
