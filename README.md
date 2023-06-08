# credit-risk-classification
Supervised learning



![image](https://github.com/romymontalva/credit-risk-classification/assets/119911640/a26f293b-8515-4ff7-b230-01fdbf7fbd9c)


<b>OVERVIEW:</b>
In this project, machine learning techniques were used to train and evaluate a model based on loan risk.
In this proyect we used machine learning techniques and pandas language in python. 
We obtained a data of lending activities from a lending company, this allowed us to analized and predict the loan risk and be able to determined wether the loan is healthy or high risk:
"y value": loan status that indicates if a loan is healthy or at high risk
"x values" : independent variables like loan size, interest rate, borrower income, debt to income ratio, number of accounts and derogatory marks.
Data was split into testing sets and training. The training set was used to create Logistic Regression Model using the LogisticRegression module. 
Using the testing feature data and the fitted model and also predictions on the testing data labels were generated. 
The model's performance was evaluated using confusion matrix and classification report and two logistic regression models were created.


<b> WHY TO USE IT? </b>
A primary function of a risk rating model is to assist in the underwriting of new loans. As well, risk rating assists management in predicting changes to portfolio quality and the subsequent financial impact of such changes.
A bank's profit or a loss depends to a large extent on loans i.e. whether the customers are paying back the loan or defaulting. By predicting the loan defaulters, the bank can reduce its Non- Performing Assets.

<b>DESCRIPTION:</b>





<b>Logistic Regression Model using the original data:</b>


![image](https://github.com/romymontalva/credit-risk-classification/assets/119911640/93805f32-5c3e-4e33-951a-4e54fb2941c1)








<b>Precision</b> : Healthy Loan - 100% High Risk loan - 85%

<b>Recall</b> : Healthy Loan - 99% High Risk loan - 91%


<b>f1-score</b> : Healthy Loan - 100% High Risk loan - 88%

Balanced Accuracy Score: 95%





<b>Logistic Regression Model using the Oversampled data:</b>


![image](https://github.com/romymontalva/credit-risk-classification/assets/119911640/a409d5da-4ae2-4397-aba0-d0ae899853d7)





  

<b>Precision</b> : Healthy Loan - 99% High Risk loan - 99%

<b>Recall</b> : Healthy Loan - 99% High Risk loan - 99%

<b>f1-score</b> : Healthy Loan - 99% High Risk loan - 99%

Balanced Accuracy Score: 99%

<b>SUMMARY:</b>

In our analysis we got very high accuracy porcentages scores, finding in the Logistic Regression Model a balanced accuracy score of 99% in the oversampled data while with the Logistic regression model using the original data we got 95% accuracy. So we can summarize, stating that for this type of data the perdect fit will the the Logistic regression model. 
Also we can state that predicting supports the development of critical thinking skills by requiring students to draw upon their prior knowledge and experiences as well as observations to anticipate what might happen. In this case credit risk evaluation has a relevant role to financial institutions, since lending may result in real and immediate losses and this tool can be used by banks as well as financial institutions. 

