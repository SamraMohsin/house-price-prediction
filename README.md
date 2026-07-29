# House Price Prediction

This project uses the Kaggle **House Prices - Advanced Regression Techniques** dataset to build a simple regression model in Python.

## What the notebook does

- Loads `train.csv` with pandas
- Checks the data shape, missing values, data types, and summary statistics
- Uses 5 simple features: `OverallQual`, `GrLivArea`, `GarageCars`, `TotalBsmtSF`, and `YearBuilt`
- Trains a `LinearRegression` model with scikit-learn
- Evaluates the model with RMSE and R²
- Plots actual vs. predicted house prices

## Why these features were chosen

- `OverallQual` because house quality usually affects price a lot
- `GrLivArea` because bigger living space usually means a higher price
- `GarageCars` because garage size can add value
- `TotalBsmtSF` because basement space is useful extra area
- `YearBuilt` because newer houses often sell for more

## Files in this project

- `house_prices_linear_regression.ipynb` - main notebook for the assignment
- `requirements.txt` - Python packages needed to run the notebook
- The Kaggle CSV files are kept out of GitHub, so you will need to download them yourself

## How to run

1. Open `house_prices_linear_regression.ipynb` in Jupyter Notebook or Google Colab.
2. Install the Python packages in `requirements.txt` if they are not already installed.
3. Download `train.csv` from Kaggle and put it in the same folder as the notebook.
4. Run the cells from top to bottom.

## Getting the data

The notebook uses the Kaggle version of the House Prices dataset. I kept the data files out of the GitHub repo because they are fairly large and Kaggle already provides them.

If you are using Google Colab, upload `train.csv` before running the notebook.

## Notes

This is a beginner-friendly project, so the model is intentionally simple. It gives a decent first look at regression, but it is not meant to be the best possible solution for the Kaggle competition.