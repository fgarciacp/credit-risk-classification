# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting the status of loans. 
The data consists of various financial indicators such as loan size, interest rate, borrower income, debt-to-income ratio, 
number of accounts, derogatory marks, and total debt. The target variable is loan_status, where 0 indicates a healthy loan and 1 indicates 
a high-risk loan.

-Data Preprocessing:

Features (X) and labels (y) were separated.
The dataset was split into training and testing subsets using a random state of 1.
-Model Selection:

Logistic regression was chosen due to its suitability for binary classification problems.
-Model Training:

The model was trained on the training data using the LogisticRegression module from scikit-learn.
-Evaluation:


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.
Confusion Matrix:
[[18655   110]
 [   36   583]]
Accuracy: 99.2%

Precision: 84.1% (for high-risk loans, label 1)

Recall: 94.2% (for high-risk loans, label 1)

## Summary

The logistic regression model performs exceptionally well in predicting both healthy loans (0) and high-risk loans (1). 
Key observations include:

Strengths: The model achieves a high overall accuracy of 99.2%. It correctly classifies most healthy loans, and the precision for high-risk 
loans is strong at 84.1%.
Weaknesses: While recall for high-risk loans is high (94.2%), some false positives and false negatives still exist.

This model is well-suited for the task of loan risk prediction. However, given the importance of minimizing false negatives 
(unidentified high-risk loans), further optimization or the use of additional models could enhance performance.
