# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Purpose: You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
* Data provided: income, debt to income, total debt, number of account, loan information
* Data that needed predicting: creditworthiness (if something was a healthy loan or high risk loan)
* loan_status   0 represents healthy loans, 1 represents high risk loans based on 77536 accounts
0    75036
1     2500
*   Stage 1: read data and separate into features and target
    Stage 2: split the data and fit the model using the split data
    Stage 3:evaluate performance by creating a confusion matrix
* Model that was used was LogisticRegression due to there being binary components within the target- which was whether it was a healthy or high risk loan (two categories)

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    *Accuracy: 0.99
    *Recall: 0.99 (healthy) 0.94 (highrisk)
    *Precision: 1.0 (healthy) 0.84 (highrisk)
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use:

Since the company end goal is to predict the creditworthiness of borrowers, the recall for highrisk loans has to be high in order to make sure that the model is correctly identifying highrisk loans (this reduces the risk of approving loans to high risk individuals). Precision should also be high with the highrisk class because higher precision leads to less false positives reducing the likelihood of rejecting a creditworthy applicant. In the case of the model shown above, it has a high recall for high risk loans (94%), but it does not have a high precision (84%), which can lead to creditworthy applicants being denied. Due to this I do not recommend this model, it should be optimized for a higher precision of at least 90% and keeping the high recall to give the best results. 