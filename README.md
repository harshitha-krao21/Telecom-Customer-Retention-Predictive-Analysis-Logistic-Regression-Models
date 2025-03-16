# Telecom-Customer-Retention-Predictive-Analysis-Train-Logistic-Regression-Models
Using the customer Churn dataset, a Logistic Regression model is fit that predicts if a customer will exit. Used the logistic regression model with three different regularization hyperparameters (No regularization, L1, L2)

# Introduction: Telecom Customer Retention

Imagine you are a data scientist in the marketing department at a telecom company. Recently, in a department meeting, the leadership emphasized the critical importance of customer retention. In your role, you have access to a comprehensive dataset from your organization's database. This data contains a wealth of information, from basic customer demographics to their frequency of use and the results of their churn.

You're tasked with delving into this dataset to uncover insights that can help improve customer retention. Think of yourself as a data scientist, providing actionable data-driven suggestions based on your quantitative analysis.

You have at your disposal various data analysis techniques, ranging from basic statistical analysis to complex predictive modeling. Your challenge is to use these tools effectively to extract meaningful insights from the dataset.

Anonymous Customer ID

Call Failures: number of call failures

Complains: binary (0: No complaint, 1: complaint)

Subscription Length: total months of subscription

Charge Amount: Ordinal attribute (0: lowest amount, 9: highest amount)

Seconds of Use: total seconds of calls

Frequency of use: total number of calls

Frequency of SMS: total number of text messages

Distinct Called Numbers: total number of distinct phone calls

Age Group: ordinal attribute (1: younger age, 5: older age)

Tariff Plan: binary (1: Pay as you go, 2: contractual)

Status: binary (1: active, 2: non-active)

Churn: binary (1: churn, 0: non-churn) - Class label (Outcome Variable)

Customer Value: The calculated value of the customer

# Steps:

# Preprocessing Data

# Fitting a Logistic Regression on Your Training Data¶

After defining X and y, created the following models and trained them:

LogisticRegression with No Regularization

LogisticRegression with L1 and C=10

LogisticRegression with L2 and C=10

Used k-fold cross-validation to assess the performance of the models.

Reported the performance (accuracy, recall, precision, f-1 score) for each model.

# Predict with Your Selected Model, and Save the Results
