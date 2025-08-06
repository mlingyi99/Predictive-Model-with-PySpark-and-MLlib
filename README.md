# Predictive-Model-with-PySpark-and-MLlib
## Introduction
#### In this project, you will explore how to build a predictive classification model using PySpark and its machine learning library, MLlib. Working with a real-world dataset of loan applications, your goal is to develop and evaluate models that predict loan approval outcomes based on various applicant features. This hands-on assignment is designed to give you practical experience with key stages of the machine learning pipeline in a distributed computing environment, including data preprocessing, feature engineering, model selection, and evaluation. By completing this assignment, you will deepen your understanding of working with big data tools and applying machine learning techniques to make informed predictions.
## Learning Objectives
By the end of this project, you will be able to:
#### ● Apply data preprocessing techniques in PySpark, including handling missing values, detecting and managing outliers, and transforming continuous variables through discretization.
#### ● Perform feature selection and engineering, justifying the inclusion or exclusion of features for predictive modeling.
#### ●Implement categorical data encoding using label encoding in preparation for machine learning workflows in PySpark.
#### ● Build and evaluate multiple classification models—such as Logistic Regression, Decision Tree, Random Forest, Naive Bayes, or K-Nearest Neighbors—using PySpark’s MLlib library.
#### ● Interpret and compare model performance using accuracy scores to determine the most effective classifier for predicting loan approval.
#### ● Write and document the end-to-end machine learning pipeline, including preprocessing choices, modeling decisions, and output results in a reproducible and readable format.
## Reuqirements
#### ● For this project, you will need to predict whether or not a person will get a loan.
#### ● Check for missing values. If there are any missing values, deal with them appropriately.
#### ● Provide written justification explaining why you selected particular methods for dealing with missing values
#### ● Check for outliers. Do we keep them or do we drop them? Why?
#### ● Provide a written justification explaining why you decided to keep or drop outliers.
#### ● Discretize the following columns and explain why you chose particular discrete categories/ranges for the values:
○ ApplicantIncome
○ CoapplicantIncome
○ LoanAmount
○ Loan_Amount_Term
#### ● Think about which features make sense as predictors. DO NOT use all features as predictors in your model.
#### ● Provide a written justification explaining why you selected certain features and excluded others.
#### ● For categorical columns (after you’ve dealt with missing values and after you have reduced the number of categories) make sure to LabelEncode your values
#### ● Train and evaluate three classification models, using any combination of Naive Bayes, KNN, LogisticRegression, DecisionTree, or RandomForest algorithms. Your models must predict the Loan_Status.
#### ● Report each model’s accuracy score.
#### ● Output the model’s accuracy scores to a text file titled output.txt.
