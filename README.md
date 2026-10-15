# House Price Prediction 

## Overview

This project uses machine learning to predict house sale prices based on housing features such as living area, overall quality, year built, and garage capacity.

Built using Python, pandas, and scikit-learn in Google Colab.

## Dataset

The project uses the [Kaggle House Prices: Advanced Regression Techniques dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

The training data contains house features and their sale prices. The test data contains house features for which prices must be predicted.

## Project Workflow

* Explored and analyzed the housing dataset.
* Handled missing numerical and categorical values.
* Encoded categorical features using one-hot encoding.
* Trained regression models to predict sale prices.
* Evaluated model performance using Mean Absolute Error (MAE).
* Got reduction in MAE as more parameters were considered into consideration

## Models and Results

* Linear Regression with Multiple Variables/Parameters
* Linear Regression

Used a Linear Regression model trained on numerical and categorical housing features after preprocessing missing values and encoding categorical variables.

Evaluation metric: Mean Absolute Error (MAE)

Validation MAE: $20,466.13

This means that, on the validation set, the model's predictions differed from the actual sale prices by an average of approximately $20,466.

## Tools and Libraries

* Python
* pandas
* NumPy
* Matplotlib and Seaborn
* scikit-learn
* Google Colab
