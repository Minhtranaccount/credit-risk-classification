# Module 12 Report Template

## Overview of the Analysis

* This data analysis uses historical lending activity from a lending services company to build a model that can identify the creditworthiness of borrowers.
Based on the information of provided examples, it builds a model via Machine Learning - Logistic Regression method to predict future outcome. 
A value of 0 in the “loan_status” column means that the loan is healthy. 
A value of 1 means that the loan has a high risk of defaulting.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

                            precision    recall  f1-score   support

   Healthy Loan (Low Risk)       1.00      1.00      1.00     18759
Unhealthy Loan (High Risk)       0.87      0.89      0.88       625

                  accuracy                           0.99     19384
                 macro avg       0.94      0.94      0.94     19384
              weighted avg       0.99      0.99      0.99     19384


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
                            precision    recall  f1-score   support

   Healthy Loan (Low Risk)       1.00      1.00      1.00     18759
Unhealthy Loan (High Risk)       0.87      1.00      0.93       625

                  accuracy                           1.00     19384
                 macro avg       0.94      1.00      0.96     19384
              weighted avg       1.00      1.00      1.00     19384


## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Both models have good accuracy  score and Healthy Loan scores.
* However, model 2 witnesses the higer Unhealthy Loan recall percentage indicating that Model 2 is better to use.


