# credit-risk-classification\

* The purpose of the analysis on our data set was to predict the probability of loans being low or high risk
* From the data provided using information such as loan size, interest rate, income, debt-to-income, etc we try to accurately predict the      risk of a loan
* Next we create a variable to count the number of defaulted loans (2500)
* After we split the data into our target (loan status) and feature variables, we do this to create our training and testing data for our machine learning
* We use logistic regression since we want to classify loans being low or high risk



* The accuracy of our model is 99%, it is an almost perfect model to predict loan risk
* The precision for low risk was at 100% whereas high risk had an 85% accuracy
* The recall values for low and high were at 99% and 91% respectively

Although the f1 score for high risk loans could be higher, I would recommend using this model. These loans could cost the banks money so it is important to consider this
