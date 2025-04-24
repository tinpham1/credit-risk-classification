# Credit Risk Classification

## Overview of the Analysis

The purpose of this analysis is to develop a machine learning model that can predict the creditworthiness of borrowers using historical loan data from a peer-to-peer lending service. We focus on classifying loans as either **healthy (0)** or **high-risk (1)** using logistic regression, which is well-suited for binary classification problems like this one.

## Results

- **Accuracy Score**: 0.99  
- **Precision Score**:  
  - Healthy Loans (0): 1.00  
  - High-Risk Loans (1): 0.84  
- **Recall Score**:  
  - Healthy Loans (0): 0.99  
  - High-Risk Loans (1): 0.94  

## Summary

The logistic regression model performs exceptionally well at predicting healthy loans and fairly well at detecting high-risk loans. The model’s high overall accuracy and strong recall for high-risk loans suggest it is effective at identifying most potential defaults, which is critical for financial risk management. Given its performance and interpretability, I recommend this model for use by the company as a strong starting point for assessing borrower risk. Further refinements or using additional models could help improve precision for high-risk predictions.
