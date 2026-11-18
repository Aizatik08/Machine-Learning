# Practical Work 3 — Data Preprocessing

## Dataset

Titanic Passenger Dataset.

Source:
https://github.com/mwaskom/seaborn-data

## Objective

Build a preprocessing pipeline using Pipeline and ColumnTransformer.

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Preprocessing Methods

- Median imputation for numerical features.
- Constant imputation with "Unknown" for categorical features.
- StandardScaler for numerical features.
- OneHotEncoder for categorical features.

## Data Leakage Prevention

The dataset was split into training and testing sets before preprocessing.

The pipeline was fitted only on training data and applied to test data using transform().

## Project Structure

- data/ — dataset
- notebooks/ — analysis and preprocessing
