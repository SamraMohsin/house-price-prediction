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
- `train.csv`, `test.csv`, `sample_submission.csv`, `data_description.txt` - Kaggle dataset files and reference files

## How to run

1. Open `house_prices_linear_regression.ipynb` in Jupyter Notebook or Google Colab.
2. Install the Python packages in `requirements.txt` if they are not already installed.
3. Run the cells from top to bottom.

## Getting the data

The Kaggle dataset files are included in the repository now, so the notebook can be opened and run from the same folder without downloading extra files first.

## Notes

This is a beginner-friendly project, so the model is intentionally simple. It gives a decent first look at regression, but it is not meant to be the best possible solution for the Kaggle competition.