# Retail Customer Analytics: RFM Segmentation and Predictive Modeling

## Project Overview

This project explores customer purchasing behavior using the UCI Online Retail II dataset, which contains over one million retail transaction records from 2009 to 2011.

The objective was to identify valuable customer segments, understand repeat purchasing behavior, and develop machine learning models to predict future purchases.

## Tools and Technologies

1. Python (Pandas, NumPy, Matplotlib, Scikit-learn)

2. SQL (SQLite)

3. Jupyter Notebook

4. Logistic Regression

5. Random Forest

## Key Findings

Analyzed 779,425 cleaned transaction records representing 5,878 unique customers.

Identified that approximately 11% of customers generated 65.64% of cleaned revenue.

Found that 72.39% of customers made repeat purchases.

Achieved 71.05% accuracy using Logistic Regression.

Achieved 71.43% accuracy using Random Forest.

Identified Recency and Monetary value as the strongest Random Forest predictors.

## Machine Learning Methodology

Historical customer transactions were used to calculate Recency, Frequency, and Monetary (RFM) features.

Two classification models were trained to predict whether customers would make another purchase during a subsequent observation period.

Model performance was evaluated using accuracy, precision, recall, and F1-score.

A preliminary temporal comparison produced approximately 70% accuracy. Because the historical windows overlap, this result should not be considered fully independent chronological validation.

## Project Files

View the Complete Analysis Notebook

rca.ipynb — Main Python, SQL, and machine learning notebook.

feature_importance.png — Random Forest feature-importance visualization.

model_results.csv — Model performance summary.

## Dataset

Source: UCI Online Retail II

The original dataset is not included in this repository due to its size.

## Limitations and Future Work

Future improvements include independent chronological validation, additional customer behavior features, hyperparameter tuning, and more detailed evaluation of customer retention predictions.

## Conclusion

This project demonstrates practical experience with data cleaning, SQL analysis, customer segmentation, feature engineering, and machine learning. It highlights how transactional data can be used to identify customer patterns and inform business decisions.
