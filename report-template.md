# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    The purpose of this analysis was the predict loan status of healthy loans or high-risk loans based on features within the dataset.
* Explain what financial information the data was on, and what you needed to predict.
    Loan size, interest rate of the lone, income of the borrower, debt to income ratio, number of accounts the borrower has, derogatory marks, and borrower's total debt. We used all of these in the X variable of the model.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`). We were trying to predict loan status. Loan status was the target variable.
* Describe the stages of the machine learning process you went through as part of this analysis. I loaded the data from the CSV file, split the data into features and labels (X and y), and split the data into training and testing. I used Logistic Regression to build the first model and it was trained using the training data (X_train and y_train). Then we evaluated the model.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms). LogisticRegression

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.
* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    Accuracy scored 99% which means the model predicts correctly 99% of the time, which is high.
    Precision scored 1 for Healthy Loan (0), which is perfect precision. 
    Precision scored .86 for High-Risk Loan (1), which means 86% of predicts are correct, but there are 14% false positives.
    Recall scored .99 for Healthy Loan and .94 for High-Risk Loan. Very small number of false negatives.
    
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
    We used logistics regression  which performed well, but there is room for improvement on the high-risk loan prediction. Random Forecast would be another one that could handle the class imbalance better.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) 
    It is important to predict high-risk loans. We need to improve the model's recal for high-risk loans to minimize missed predictions.

If you do not recommend any of the models, please justify your reasoning.
