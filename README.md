# credit-risk-classification
Supervised learning


<b>OVERVIEW:</b>
In this project, machine learning techniques were used to train and evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company was used to build a model that can identify the creditworthiness of borrowers.
In this proyect we used machine learning techniques and pandas language in python. 
We obtained a data of lending activities from a lending company, this allowed us to analized and predict the loan risk and be able to determined wether the loan is healthy or high risk:
"y value": loan status that indicates if a loan is healthy or at high risk
"x values" : independent variables like loan size, interest rate, borrower income, debt to income ratio, number of accounts and derogatory marks.
Data was split into testing sets and training. The training set was used to create Logistic Regression Model using the LogisticRegression module. 
Using the testing feature data and the fitted model and also predictions on the testing data labels were generated. 
The model's performance was evaluated using confusion matrix and classification report and two logistic regression models were created.

<b>DESCRIPTION:</b>





<b>Logistic Regression Model using the original data:</b>
Balanced Accuracy Score: 95%
Precision : Healthy Loan - 100% High Risk loan - 85%
Recall : Healthy Loan - 99% High Risk loan - 91%
f1-score : Healthy Loan - 100% High Risk loan - 88%




<b>Logistic Regression Model using the Oversampled data:</b>
  
Balanced Accuracy Score: 99%
Precision : Healthy Loan - 99% High Risk loan - 99%
Recall : Healthy Loan - 99% High Risk loan - 99%
f1-score : Healthy Loan - 99% High Risk loan - 99%


<b>SUMMARY:</b>
