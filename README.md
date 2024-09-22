# House Price Prediction - Machine Learning Model

## Overview
This repository contains the machine learning project for predicting house prices using several regression techniques. The project explores various aspects of machine learning from data preparation to model evaluation, emphasizing feature engineering and hyperparameter tuning.

## Features
- Data exploration and visualization to understand the distribution and correlation of features.
- Implementation of multiple regression models including Linear Regression, Decision Tree, and Random Forest.
- Extensive hyperparameter tuning and model evaluation using R² as the metric.
- Feature engineering through Recursive Feature Elimination (RFE) and manual feature selection to enhance model performance.

## Technologies Used
- Python
- Pandas, Numpy for data handling.
- Matplotlib, Seaborn for data visualization.
- Scikit-Learn for modeling and evaluation.

## Dataset
The project utilizes a dataset containing various features of housing data such as `MedInc`, `HouseAge`, `AveRooms`, `AveBedrms`, `Population`, `AveOccup`, `Latitude`, and `Longitude`. The target variable is `MedHouseVal`.

## Model Performance
The best performing model was a Random Forest regressor which achieved an R² score of 0.839755 on the test data, demonstrating a robust prediction capability for house prices.
