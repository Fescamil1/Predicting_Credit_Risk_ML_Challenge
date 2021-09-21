# Predicting_Credit_Risk_ML_Challenge
Supervised Machine Learning Homework - Predicting Credit Risk. The end goal is to build a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not. 

## Background

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

Use this data to create machine learning models to classify the risk level of given loans. Compare the Logistic Regression model and Random Forest Classifier.

## Fit a Logistic Regression model and Random Forest Classifier model

Create a Logistic Regression model, fit it to the data, and print the model's score. Do the same for a Random Forest Classifier. 

**INITIAL PREDICTION:** 

When working with data that is more linearly separable Logistic Regression Model seems to be a better fit. However, when working with more "real world"data it is difficult to find it to be linearly separable. In most cases it is a messy and with outliers.  Therefore, because the data that we are working with has a very large number of variables/features, I  believe that the Random Forest Classifier model will do much better than the  Logistic Regression Model. 

Unscaled Logistic Regression Result: 

![image-20210920212220433](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210920212220433.png)

Unscaled Random Forest Classifier Result:

![image-20210920212338200](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210920212338200.png)

 As expected, Random Forest Classifier model did scored better than the Logistic Regression Model. However, the test score difference was not as significant as I had expected. 

I expected scaling to improve the Logistic Regression scores but surprisingly they dropped slightly. Nonetheless, Random Forest Classifier model did improve on test score. 

![image-20210920214320167](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210920214320167.png)

