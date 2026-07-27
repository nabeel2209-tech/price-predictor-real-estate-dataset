# Price Predictor — Real Estate Dataset

A machine learning project that predicts real estate prices using linear regression, built with pandas, numpy, and scikit-learn.

## Overview

This project loads a housing dataset, performs data cleaning and feature preparation, trains a linear regression model, and evaluates it using standard regression metrics such as MAE, MSE, and R2.

## Dataset

The dataset used is the Housing Price Prediction Dataset from Kaggle, available at https://www.kaggle.com/datasets/ameyac11/housing-price-prediction-dataset. The CSV file (housing_price_dataset.csv) is included in this repository at the root level for convenience.

## Getting Started

Clone this repository, then install the required packages: pandas, numpy, matplotlib, seaborn, and scikit-learn. Open SOURCECODE_Project_1_final.ipynb in Jupyter or Google Colab. Before running, make sure the dataset path in the notebook points to the local CSV file using this line:

df = pd.read_csv("housing_price_dataset.csv")

This replaces the original hardcoded local file path used during development.

## Tech Stack

Python, pandas, numpy, scikit-learn (LinearRegression, train_test_split, StandardScaler), and matplotlib/seaborn for visualization.

## License

This project is for educational and portfolio purposes. Dataset credit goes to the original Kaggle contributor linked above.
