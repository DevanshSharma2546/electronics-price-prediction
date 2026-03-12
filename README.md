# Electronics Price Prediction

This project builds a machine learning model to predict the selling price of electronic products using product specifications, ratings, and marketplace indicators.

## Project Overview

The goal of this project is to estimate the price of electronic products listed on online marketplaces using historical product data and engineered features.

The model analyzes factors such as:

* product ratings
* number of reviews
* sales trends
* discount percentage
* extracted product specifications (RAM, storage, brand)

## Feature Engineering

To improve prediction accuracy, additional features were created:

* **popularity_score** = reviews × rating
* **price_per_review**
* RAM extraction from product titles
* Storage extraction from product titles
* Brand extraction from titles
* Product category classification

## Machine Learning Models Used

Multiple regression models were trained and compared:

* Linear Regression
* Ridge Regression
* Decision Tree Regressor
* Random Forest Regressor

## Best Model

Random Forest Regressor achieved the best performance.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Repository Structure

electronics-price-prediction
│
├── electronics_price_prediction.ipynb
├── project_report.pdf
├── requirements.txt
└── README.md

## Author

Devansh Sharma
