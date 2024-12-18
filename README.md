# Property-price-prediction

# House Price Prediction Model

## Overview
This project involves building a machine learning model to predict house prices. The model utilizes linear regression and incorporates techniques for handling outliers and data discrepancies to improve accuracy.

## Key Features
- **Outlier Removal**: Identified and removed outliers using the Interquartile Range (IQR) method. For instance, houses priced above 1.5 times the IQR were excluded from the dataset.
- **Data Discrepancy Handling**: Addressed issues like missing values and inconsistent data formats. For example, normalized the square footage values to ensure uniformity across the dataset.

## Model Implementation
1. **Initial Model**: Implemented a basic linear regression model to establish a baseline for predictions.
2. **K-Fold Cross Validation**: Employed K-Fold cross-validation (k=5) to ensure the model's robustness and to mitigate overfitting.
3. **Grid Search CV**: Utilized Grid Search Cross-Validation to optimize hyperparameters, improving model performance by fine-tuning parameters like learning rate and regularization strength.

## Conclusion
This project demonstrates effective techniques for preprocessing data and building a predictive model for house prices. The combination of linear regression, k-fold cross-validation, and grid search enhances the model's reliability and accuracy.

## Usage
To run the model:
1. Clone the repository.
2. Install the required packages.
3. Run the `main.py` script to see predictions based on the cleaned dataset.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib

