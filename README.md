# **BANK CUSTOMER CHURN PREDICTION PROJECT**

# INTRODUCTION-

## A Bank is a financial institution licensed to receive deposits and make loans. Banks may also provide financial services such as wealth management, currency exchange. When new customers start buying and/or using a product in a bank, each new user contributes to the bank product’s growth rate. Certainly, some of those customers in due course will stop their utilization or end their subscription; this could be because they switched to a competitor, no longer need the bank services, they’re unhappy with their user experience, or they can no longer afford the cost. The customers that stop using the bank products are the “churn” for a given period. Which can be can be a monthly, quarterly, or annual churn rate at the bank. This leads to the importance of churn management in organizations such as a bank.

## So,I build a predictive model using machine learning algorithms to identify bank customers who are at a risk of churning, enabling proactive retention strategies and minimizing customer attrition.I use the public dataset that contains 10000 rows and 14 columns and Exited is the target variable column in this case.It contains the following information about customers as-
## •	Credit Score- Credit score of the customer

## •	Geography- The country from which the customer belongs

## •	Gender- Male or Female

## •	Age- Age of the customer

## •	Tenure- Number of years for which the customer has been with the bank. Balance- Bank balance of the customer

## •	Num of Products- Number of bank products the customer is utilizing (savings account, mobile banking, internet banking etc

## •	Has Cr Card- Binary flag for whether the customer holds a credit card with the bank or not

## •	Is Active Member- Binary flag for whether the customer is an active member with the bank or not

## •	Estimated Salary- Estimated salary of the customer in Domain

# STEPS-

## 1]Data collection- 
Collect the customer data from various sources.  

## 2]Data preprocessing- 
Preprocess the data by cleaning, transforming, and normalizing it to prepare it for analysis.

## 3]Exploratory data analysis- 
Analyze the data to identify missing values, patterns, outliers, correlations and insights that can be used to predict churn.

## 4]Feature engineering- 
Use feature engineering techniques to select and create the most predictive features for the model.

## 5]Model selection and training- 
I have choosen 5 ML algorithms and trained them on train data by implementing following steps as:-
## A) Logistic regression –
a.	Import the Logistic Regression model from sklearn.linear_model.
b.	Create an instance of Logistic Regression model.
c.	Now train the model.
d.	Perform the prediction.
e.	Check the accuracy score, precision score, recall score & F1 score. Draw the classification report.
f.	Draw the confusion matrix.
g.	Draw the ROC-AUC curve.

## B) KNearest Neighbour –
a.	Import the KNeighborsClassifier model from sklearn.neighbors
b.	Create an instance of KNeighborsClassifier model.
c.	Now train the model.
d.	Perform the prediction.
e.	Check the accuracy score, precision score, recall score & F1 score. Draw the classification report.
f.	Draw the confusion matrix.
g.	Draw the ROC-AUC curve.

## C) Decision Tree –
a.	Import the DecisionTreeClassifier model from sklearn.tree
b.	Create an instance of DecisionTreeClassifier model.
c.	Now train the model.
d.	Perform the prediction.
e.	Check the accuracy score, precision score, recall score & F1 score. Draw the classification report.
f.	Draw the confusion matrix.
g.	Draw the ROC-AUC curve.

## D) Random Forest –
a.	Import the RandomForestClassifier model from sklearn.ensemble
b.	Create an instance of RandomForestClassifier model.
c.	Now train the model.
d.	Perform the prediction.
e.	Check the accuracy score, precision score, recall score & F1 score. Draw the classification report.
f.	Draw the confusion matrix.
g.	Draw the ROC-AUC curve.

## E) Gradient Boosting–
a.	Import the GradientBoostingClassifier from sklearn.ensemble
b.	Create an instance of GradientBoostingClassifier model.
c.	Now train the model.
d.	Perform the prediction.
e.	Check the accuracy score, precision score, recall score & F1 score. Draw the classification report.
f.	Draw the confusion matrix.
g.	Draw the ROC-AUC curve.

## 6]Model Evaluation- 
Evaluate the model’s performance on dataset using appropriate metrices such as accuracy score, precision score, recall score, F1 score and ROC-AUC. 

## 7]Save the best model for prediction- 
Save the model with the best accuracy score, precision score, recall score, F1 score and ROC-AUC. 

## 8]User interface development- 
Develop a user interface that allows bank managers and customer service representatives to input customer data, view churn predictions. It should also allow for real-time monitoring and reporting of churn metrics.

# OUTPUT-

## Output for this project is a binary label that indicates whether a customer is likely to churn or not. The model’s output can also provide insights into the factors that contribute to customer churn. This information can be used to identify areas for improvement in bank’s services and processes to reduce churn. 






