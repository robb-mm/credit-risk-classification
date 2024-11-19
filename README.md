# Credit Risk Analysis Report

## Overview

This analysis evaluates the fitness of the machine learning model Logistic Regression to identify the creditworthiness of borrowers. To do so, the model takes a lending activity dataset, uses its 7 features and 1 target label 'loan status' to train itself and to predict the loan status. To account the model's robustness to predict, the dataset is split into two sets, first 75% to train the model and remaining 25% to predict the target. To conclude if the model is good, metrics such as accuracy, precision and recall scores are generated and assessed.

## Results

* Logistic Regression Model:
    * Accuracy is 0.994, very close to 1. The prediction of samples labels matches the actual labels, 99 out of 100 times.
    * Precision is 1 for healthy loans, 0.87 for high-risk loans. Model can predict healthy loans correctly always and high risk loans 87% of the time only.
    * Recall is 1 for healthy loans, 0.95 for high-risk loans. Model found all healthy loans and only 95% high risk loans.

## Summary

From the classification report, the model accuracy is 0.99, a good predictor of loan risk type 99% of the time. However, the precision and recall metrics would indicate that accuracy mostly applies to healthy loans, as the model correctly found all healthy loans while only 95% high risk loans. Given that, the model can be recommended only if the company is open to not finding the 5% high risk loans. Conversely, on the positive side, the model can always help find the borrowers with good credit.
