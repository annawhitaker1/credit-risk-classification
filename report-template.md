# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to build a logistic regression model to predict the risk of loans based on features within the lending data set. The dataset contains information regarding loan applications. It includes features such as loan size, loan interest rate, income of the borrower, debt to income ratio, number of accounts the borrower has, derogatory marks, and borrower's total debt. We used loan status, (0) = healthy and (1)= high-risk, as the target variable and the remaining columns listed above as our features.

## Data Preprocessing and Model Training


The dataset was loaded from a CSV file and preprocessed for cleaning prior to loading it into the model for training. The target variable and feature variables were split. Then, the data was split into training and testing sets. A Logistic Regression model was trained with the training data set and evaluated with the testing data to verify it's performance.

## Results 

The logistic regression model achieved the following performance metrics:
- **Accuracy:** 0.99
- **Precision for 0 (healthy loan):** 1.00
- **Recall for 0 (healthy loan):** 0.99
- **F1-score for 0 (healthy loan):** 1.00
- **Precision for 1 (high-risk loan):** 0.86
- **Recall for 1 (high-risk loan):** 0.94
- **F1-score for 1 (high-risk loan):** 0.90
The model was successful in predicting  healthy and high-risk loans, with an accuracy score of 0.99. The precision, recall, and F1-score are all above the threshold to show that it is effective in identifying both types of loans.

## Summary

The logistic regression model preformed well and effectively predicted loan outcomes. However, there is room for improvement with additional iterations to further optimize and improve the model's performance. It is important to predict high-risk loans. We need to improve the model's recall for high-risk loans to minimize missed predictions.

 ## Recommendations

Based on this analysis, Random Forecast or Logistic Regression could be used to handle the class imbalance better. But, logistic regression may be the better of the two. 





