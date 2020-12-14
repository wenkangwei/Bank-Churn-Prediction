# Bank-Churn-Prediction
# Motivation
The goals of this project are following:
visualize and identify the factors/features that contributes to the churn of customers
Construct and train a machine learning model to predict the possibility of churns and help custumer service target the factors that may lead to churn and prevent customer churn, reduce loss of profit

# Dataset
The dataset is from [kaggle](https://www.kaggle.com/adammaus/predicting-churn-for-bank-customers)
There are 14 attributes in the dataset. The information of the dataset is shown as follow:
+ **RowNumber** — the record (row) number and has no effect on the output.
+ CustomerId — contains random values and has no effect on customer leaving the bank.
+ **Surname** — the surname of a customer has no impact on their decision to leave the bank.
+ **CreditScore** — can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
Geography — a customer’s location can affect their decision to leave the bank. 
+ **Gender** — it’s interesting to explore whether gender plays a role in a customer leaving the bank. We’ll include this column, too.
+ **Age** — this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
+ **Tenure** — refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
+ **Balance** — also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
+ **NumOfProducts** — refers to the number of products that a customer has purchased through the bank.
+ **HasCrCard** — denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank. (0=No,1=Yes)
+ **IsActiveMember** — active customers are less likely to leave the bank, so we’ll keep this. (0=No,1=Yes)
+ **EstimatedSalary** — as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
+ **Exited** — whether or not the customer left the bank. This is what we have to predict. (0=No,1=Yes)

# Precedure
+	Visualized and analyzed data related to customer churn by using visualization toolkits: seaborn, matplotlib
+	Preprocessed and transforms categorical data for Machine Learning model training using pandas toolkit and normalization techniques
+	Established Data Pipeline and ML Models: Random Forest, Logistic Regression, SVM, etc. and Evaluated Models using ROC,AUC 
+	Improved Models Accuracy from 80% to 86% by using Model Selection, Cross Validation and Feature Selection,  L1 Regularization techniques


# Results and Evaluation
Please check the results in my notebook 

|model| Accuracy|	Precision	|Recall|
| - | - | - |  - |
|0|	logistic Reg|	0.8080|	0.585799|	0.194499|
|1|	KNN|	0.8308|	0.688596|	0.308448|
|2|	Random Forest|	0.8600|	0.775087|	0.440079|
|3|	SVC|	0.8572|	0.777372|	0.418468|
