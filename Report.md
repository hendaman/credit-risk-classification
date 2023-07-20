# Module 12 Report Template

## Overview of the Analysis

The purpose of the analysis is to use supervised machine learning to identify whether an individual looking to borrow funds will be of risk to the company by having the model train on previous loans provided. The dataset "lending_data.csv" contains various financial details about each borrower, which was then analysed and interpreted by the model to make predictions and assess the accuracy of the results.

The steps taken by the model was:

* Use a Logisitc Regression model created by using "Training Data"
* Predictions were then made for all line items from the dataset based off the training data.
* A confusion matrix was generated, followed by a classification report.

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

## Results

Overall the model performed well, with an accuracy score of 99%.

* Healthy Loans have an f1 score of 1.00.
* High risk loans have an f1 score of 0.88.
* Precision also showed significant results with a value of 0.99 for healthy loans and 0.91 for high risk Loans.
* Recall showed positive results of 100% for healthy loans and 85% for high risk loans.

## Summary

The model was particularly effective at predicting healthy loans with a 100% success rate, and still was very effective at flagging high risk loans 88% of the time. Whilst this can be improved, it would still be considered successful at predicting loans so I would recommend it's use.
