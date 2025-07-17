# SCT_ML_01

# 🏠 House Price Prediction Using Linear Regression

This repository contains a complete workflow for predicting house prices using a linear regression model on the [Kaggle House Prices: Advanced Regression Techniques dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

## 📊 Project Overview

The project performs:

- Data loading and exploration
- Feature engineering
- Outlier handling
- Missing value imputation
- Feature scaling
- Model training and evaluation
- Prediction on user-defined input
- Performance visualization

## 📁 Dataset

- `train.csv`: Contains training data with house features and sale prices.
- `test.csv`: Contains test data without sale prices.
- `sample_submission.csv`: Sample submission format for Kaggle.
- `data_description.txt` (optional): Description of dataset columns.

> 📌 Make sure these files are placed in the correct paths, especially when running in Kaggle or local environments.

## 📌 Requirements

You can install the required packages using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
