# California Housing Price Prediction

This project uses the California Housing Prices dataset to train an XGBoost model for predicting house prices.

## Description

The code performs the following steps:

1. **Imports libraries:** numpy, pandas, matplotlib, seaborn, sklearn, xgboost.
2. **Loads the dataset:** Uses `fetch_california_housing` from sklearn.
3. **Data exploration:** Creates a pandas DataFrame, explores data shape, missing values, and descriptive statistics.
4. **Correlation analysis:** Calculates and visualizes correlation between features using a heatmap.
5. **Data splitting:** Splits data into training and testing sets (80% train, 20% test).
6. **Model training:** Trains an XGBRegressor model.
7. **Prediction:** Predicts house prices on training and testing data.
8. **Evaluation:** Calculates R-squared error and Mean Absolute Error for both training and testing predictions.
9. **Visualization:** Creates scatter plots to compare actual vs. predicted prices for training and testing data.

## Requirements

- Python 3
- Libraries: numpy, pandas, matplotlib, seaborn, sklearn, xgboost

## Usage

1. Install the required libraries.
2. Run the code in a Jupyter notebook or Python environment.
