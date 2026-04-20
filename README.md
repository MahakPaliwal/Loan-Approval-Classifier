# Loan Approval Classifier

A machine learning model to automate loan approval decisions.

## Problem Statement
Manual loan approval is slow and inconsistent. This project builds an ML model to predict loan approval based on applicant data, making the process faster and data-driven.

## Dataset
- Source: Kaggle Loan Prediction Dataset
- Features: Gender, Married, Education, Income, Loan Amount, Credit History, Property Area etc.
- Target: Loan approval status (Yes/No)

## Approach
- Performed Exploratory Data Analysis (EDA) to understand data
- Handled missing values and outliers
- Applied feature selection and scaling
- Trained and compared multiple ML algorithms:
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Logistic Regression
  - Support Vector Machine (SVM)
- Selected best model based on accuracy and performance metrics

## Tech Stack
Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn

## How to Run
1. Open notebook in Google Colab or Jupyter
2. Upload the dataset CSV file
3. Run all cells sequentially

## Results
- Compared all 5 algorithms on accuracy and F1-score
- Random Forest gave the best performance
