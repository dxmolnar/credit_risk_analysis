![image](https://github.com/dxmolnar/credit_risk_resampling/assets/127795314/334adf8c-657c-4fcd-8024-8dc8ce7c3852)


# credit_risk_resampling
This repo is about credit risk assessment using machine learning

# Report

## Overview of the Analysis

The objective of this analysis was to develop machine learning models that can predict the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company. One of the main challenges faced in this analysis was the imbalanced nature of the data, where there were significantly more healthy loans compared to risky loans.

The provided data consisted of financial information related to loans, and the goal was to predict whether a loan would be categorized as high-risk or healthy. Although the specific variables used for prediction were not explicitly mentioned, it can be inferred that they included various financial and borrower-related features.

The machine learning process involved several stages, including data preprocessing, model training, and evaluation. Given the imbalanced dataset, special techniques were employed to address the class imbalance issue, such as utilizing resampling methods.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1:
  * Accuracy: 99.2%
  * Precision: 86% (high risk loans); 100% (low risk loans)
  * Recall: 91% (high risk loans); 100% (low risk loans)


Machine Learning Model 2:
  * Accuracy: 99.4%
  * Precision: 85% (high risk loans); 100% (low risk loans)
  * Recall: 99% (high risk loans); 99% (low risk loans)

## Summary

Both Machine Learning Model 1 and Model 2 achieved impressive accuracy scores, with Model 2 demonstrating a slightly better accuracy of 99.4%. Regarding precision, Model 1 exhibited a precision of 86% for high risk loans and a perfect precision of 100% for low risk loans, while Model 2 showcased a precision of 85% for high risk loans and a perfect precision of 100% for low risk loans.

In terms of recall, both models achieved remarkable recall rates of 99% for both low risk loans and 91% in model 1 for high risk. This indicates that both models were effective in accurately identifying the majority of high risk loans and low risk loans.

Based on these findings, it appears that Model 2 outperformed Model 1 slightly in terms of accuracy and recall for high risk loans while only fared a tiny bit worse (85 vs 86) for precision. 

