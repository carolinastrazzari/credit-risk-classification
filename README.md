# credit-risk-classification
Module 20 Challenge
Module 12 Report: Loan Risk Classification Analysis
Overview of the Analysis
The purpose of this analysis was to develop machine learning models to predict loan risk based on financial information provided in a dataset. The dataset included variables such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status (healthy or high-risk). The goal was to predict whether a loan is healthy (0) or high-risk (1) based on these features.
Basic Information about the Variables:
* Loan Status (loan_status):
* Healthy (0): 75,036 instances
* High-Risk (1): 2,500 instances
Stages of Machine Learning Process:
1. Data preprocessing: Reading the CSV file, separating features and labels, and splitting the data into training and testing sets.
2. Model training: Using logistic regression to train the machine learning model on the training data.
3. Model evaluation: Assessing the model's performance using accuracy, precision, and recall scores on the testing data.
Methods Used:
* Logistic Regression: Used to build the predictive model for loan risk classification.
Results:
* Accuracy Score: The accuracy score of the logistic regression model is 0.99, indicating a high level of overall accuracy in predicting loan risk.
* Precision Score:
* Precision for healthy loans (label 0) is 1.00, indicating almost perfect accuracy in predicting healthy loans.
* Precision for high-risk loans (label 1) is 0.85, suggesting that 85% of the predicted high-risk loans are actually high-risk.
* Recall Score:
* Recall for healthy loans (label 0) is 0.99, meaning the model correctly identifies 99% of the healthy loans.
* Recall for high-risk loans (label 1) is 0.91, indicating that the model captures 91% of the high-risk loans.
Summary:
The logistic regression model exhibits excellent performance in predicting both healthy and high-risk loans. With high precision, recall, and accuracy scores, the model demonstrates its effectiveness in identifying loan risks. The high precision for healthy loans ensures that the model accurately identifies low-risk borrowers, while the respectable precision and high recall for high-risk loans highlight its capability to flag potentially problematic cases. Therefore, I recommend using this logistic regression model as a tool for loan risk assessment by the company. Its robust performance metrics make it a reliable choice for assisting financial institutions in making informed lending decisions.

