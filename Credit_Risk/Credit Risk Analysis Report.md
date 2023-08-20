# Module 20 credit_tisk_classification Report

## Overview of the Analysis

* Purpose of the Analysis:
The purpose of this analysis was to develop machine learning models to predict loan default risk based on financial information. The goal was to create models that could effectively differentiate between healthy loans (0 class) and high-risk loans (1 class), helping financial institutions make informed lending decisions.

* Financial Information and Prediction:
The data used in the analysis contained various financial attributes related to loans. The main objective was to predict the likelihood of a loan being a high-risk loan (defaulting). This prediction is important for financial institutions to manage risks associated with lending.

* Variables to Predict:
The variable to predict was the loan_status column, where 0 indicated a healthy loan and 1 indicated a high-risk loan. 
The dataset's value_counts showed the distribution of these labels.

* Stages of Machine Learning Process:
  * The analysis followed these stages:
1. Data Loading and Splitting: The dataset was loaded into a Pandas DataFrame, and it was split into training and testing sets.
2. Model Creation: A logistic regression model was created using the training data.
3. Model Evaluation: The model's performance was evaluated using metrics such as accuracy, precision, recall, and F1-score.
4. Interpretation and Comparison: The model's performance was interpreted, and its results were compared with the business problem's   requirements.

* Methods Used:
  The primary method used for this analysis was logistic regression, which is a widely-used classification algorithm for binary prediction tasks. It was used to predict the likelihood of a loan being high-risk based on the given features.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of  machine learning model.

* Machine Learning Model：Logistic Regression
 
  * Training Set Performance:
  Accuracy: 99%
  Precision for 0: 100%
  Precision for 1: 86%
  Recall for 0: 99%
  Recall for 1: 90%
  
  * Testing Set Performance:
  Accuracy: 99%
  Precision for 0: 100%
  Precision for 1: 86%
  Recall for 0: 100%
  Recall for 1: 91%



## Summary

* Logistic Regression Model performed exceptionally well in predicting loan default risk. It demonstrated high accuracy, precision, and recall for both "0" and "1" labels on both the training and testing sets. The results indicate that the model can effectively differentiate between healthy loans and high-risk loans.

* For this particular problem of loan default prediction, where correctly identifying high-risk loans is crucial, both precision and recall for the 1 label (high-risk loans) are important. Logistic Regression Model achieves high values in these metrics, indicating that it is capable of accurately detecting high-risk loans while maintaining a high level of precision.

* Based on the results, Logistic Regression Model seems to perform the best and is recommended for deployment. It strikes a good balance between correctly identifying high-risk loans and minimizing false positives. However, further analysis, including considerations of business requirements and potential consequences of false positives and false negatives, should also be taken into account before finalizing the model choice.




