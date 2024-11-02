# Credit Risk Analysis Report

## Overview of the Analysis

This analysis looks at data relating to loans. It includes data for each loan, such as the loan size and interest rate, the income of the borrower, debt-to-income ratio, number of bank accounts, derogatory marks, and total debt. 

The provided data also included information on the loan status (healthy loan vs high-risk loan), which was removed in order to complete a Logistic Regression analysis.

This data was first placed into a dataframe with the loan status column removed. It was then split into training and testing datasets in order to prepare it to be utilized in a Logistic Regression model.

## Results

* Logistic Regression model results:
    * Accuracy: 0.99
    * Precision: Class 0 (Healthy Loan) 1.00, Class 1 (High-Risk Loan) 0.85
    * Recall: Class 0 (Healthy Loan) 0.99, Class 1 (High-Risk Loan) 0.91

## Summary

Logistic Regression was very good at modeling healthy models, being 100% precise in identifying them with the data provided. Meanwhile, it was not quite as good at determining the hig-risk loans, with only 85% precision. 

Predicting high-risk loans seems to be more important to financial instituitions as compared to predicting healthy loans, indicating the Logistic Regression may not be the best model due to it's lower precision in identifying. This means that some high-risk loans will not be identified.