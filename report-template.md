# Credit Risk Report

The purpose of this report is to predict the risk of loans based on past lending history. The dataset contains loan size, interest rate, borrower income, debt income, number of accounts, derogatory marks, and total debt.

* We used TrainTestSplit to split the data into testing and training sets
*  The loan status column indicates if a loan is either a healthy loan (0 value) or has a high risk of defaulting (1 value)
* Created a Logistic Regression Model with the original data to predict both health and high-risk loans 
* We resampled the data using RandomOverSampler then built a new Logistic Regression Model that was used to predict both health and high-risk loans

## Results


Machine Learning Model 1:
  * Accuracy : 99%
  * Precision : [(Healthy Loan, 1.00), (High-Risk Loan, .87)]
  * Recall : [(Healthy Loan, 1.00), (High_Risk Loan, .89)]



* Machine Learning Model 2:
  * Accuracy : 99%
  * Precision : [(Healthy Loan, 1.00) (High_Risk Loan, .87)]
  * Recall : [(Healthy Loan, 1.00) (High_Risk Loan, 1.00)]

## Summary

* The second Logistic regression model with the oversampled data was better at making predictions.
* In conclusion, the regrsession model with the oversampled data would be bteer to use in a real world case, would much rather have it error on the side of healthy loans and have a really high recall and precision on high-risk loans
