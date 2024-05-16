# credit-risk-classification

## Objective 

Apply various techniques to train and evaluate a model based on loan risk using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Instructions

1. Split the Data into Training and Testing Sets

2. Create a Logistic Regression Model with the Original Data

3. Write a Credit Risk Analysis Report

## Results

### Classification Report

![Classification Report](Credit_Risk/Images/classification_report_credit_risk_classification.png)

###Lostistic Regression Model

Healthy Loan 
- Accuracy 99%
- Precision 100%
- Recall 100%
- F1-Score 100%

High-Risk Loan
- Accuracy 99%
- Precision 87%
- Recall 95%
- F1-Score 100%

## Summary

The overall accuracy score of 99.4% indicates that the model is extremely close to predicting the proper loan classification every time. Further metrics such as precision and recall provide a more granular look between the labels producing a high precision and recall accuracy of 100% on healthy loans compared to 87% and 95% on high-risk loans.  Logistic regression is a good model for predicting healthy loans and high-risk loans since the f1 score on both are above 90%.  As more data becomes available, the model can be fine tuned to increase the precision score for high-risk loans. 
