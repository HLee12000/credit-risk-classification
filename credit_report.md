# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* **Purpose of the analysis** Purpose of this analysis is to see if logistic regression model can give better insight and predictions to whether a loan is considered healthy or risky. The model is used on both original and resampled(oversample) data.

* **The Dataset** the finance dataset contains lending data for loans. It includes factors such as the size, interest rate, income of borrower, debt, account number, missed payments, and the status of the loan

* **Class Distribution** Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

* **Stages of the Machine Learning Process**
Need to prepare data, by reading in, check if cleaned. 
Pick a prediction mark, for the model to attempt to predict. In this case, the loan status. 
Then split the data for training and testing.
Next, use machine learning logistic regression to begin forming our model.
Fit the model to the training samples
use test data on the model and make predictions, including matrix, accuracy, and classification report.
Do process again with resampled data and oversample process. 
compare matrix/report

* **Machine Learning Methods Utilized** Used Logistic regression, resampling and analysis tools such as confusion matrix and classification report. All of these are from SKLearn

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  Accuracy: 0.9520479254722232
  Precision: Class 0: 1.00 Class 1: 0.85
  Recall: Class 0: 0.99 Class 1: 0.91

* Machine Learning Model 2:
  Accuracy: 0.9936781215845847
  Precision: Class 0: 1.00 Class 1: 0.84
  Recall: Class 0: 0.99 Class 1: 0.99

## Summary

While both models did well, the logistic regression model using oversampled data outpreformed the original data. Precision was close, but accuracy and recall improved with oversampling. Specifically, the oversampling seems to help Class 1 to preform better. So I would reccomend oversampling logistic regression as it gives the best insight and predictions of the two. This model can possibly be used to help financial institutions better understand whether a loan is good or bad. Also, if a potential borrower could use this for personal use to see if a loan is healthy for themselves, by plugging in their own debt, income, and loan information that they are trying to apply for. 
