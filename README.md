# Loan Approval Prediction using Machine Learning
## Objective

The objective of this project is to develop a machine learning model to predict whether a loan application will be approved or rejected. The target variable, loan status, is categorical in nature, making this a classification problem.

## Business Problem

Accurate loan approval prediction helps financial institutions:

Automate the loan approval process
Reduce risk of default
Improve decision-making efficiency
Identify eligible and high-risk applicants
## Data Description
Dataset includes applicant demographic and financial details
Target Variable: Loan Status (Approved / Rejected)
Features include:
Applicant Income & Co-applicant Income
Loan Amount & Loan Term
Credit History
Education, Employment Status, and Property Area
## Approach & Methodology
### Data Preprocessing
Performed Exploratory Data Analysis (EDA) to understand data patterns and relationships
Handled missing values and treated inconsistencies
Applied encoding techniques for categorical variables
Performed feature engineering to improve model performance
### Model Building
Implemented Logistic Regression for classification
Applied GridSearchCV for hyperparameter tuning
Used a custom decision threshold to enhance prediction accuracy
### Model Evaluation
Evaluated model performance using:
Accuracy
Precision
Recall
Confusion Matrix
Classification Report
## Tech Stack
Programming Language: Python
Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
Tools: Jupyter Notebook
## Challenges
Handling missing values in key financial features
Encoding categorical variables effectively
Balancing model performance between precision and recall
Selecting optimal threshold for classification

## Conclusion

The model successfully predicts loan approval status based on applicant and financial attributes. This solution can help financial institutions make faster, data-driven, and risk-aware lending decisions.
