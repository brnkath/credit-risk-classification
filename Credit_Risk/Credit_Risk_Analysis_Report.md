# Module 20 Report

## Overview of the Analysis

The purpose of this analysis was to train and evaluate two machine learning models to evaluate loan risk using lending data in the form of a CSV file. The goal was to try and develop models that could accurately predict the creditworthiness of loan borrowers.

The dataset included 77,536 sample loans with information including loan size, interest rate, borrower income, debt-to-income, number of accounts, derogitory marks, and total debt. The target column for both models was whether the loan status was healthy or high risk for default. Logistic Regression was used for both learning models, with the resampling method of RandomOverSampler used for the second.

## Results

- Machine Learning Model 1:

  - Balance Accuracy Score: 94.42%
  - Overall Accuracy Score: 99%
  - Precision Score (weighted average): 99%
  - Recall Score (weighted average): 99%

- Machine Learning Model 2 (with resampled training data):
  - Balance Accuracy Score: 99.59%
  - Overall Accuracy Score: 100%
  - Precision Score (weighted average): 100%
  - Recall Score (weighted average): 100%

## Summary

The second model with resampled training data ended up having higher accuracy. The weighted average for both precision and recall were higher too, suggesting it would be a better model to form predictions. Though the second model provided higher accuracy, it should be noted that the precision for high-risk loans was lower at 87%.
