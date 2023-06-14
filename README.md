# My-Portfolio

# [Project 1: Multivariable Regression (Accepted Loans)](https://github.com/jlugo3059/Multivariable-Regression)

This project focuses on doing a multivariable regression on a loan’s dataset. The loans dataset comprises data from over one million borrowers who were approved to receive loans by the Lending Club company. Using the provided data, the model developed in this project will employ a multivariable regression technique to predict interest rates by considering independent variables given in the dataset.

* The data was taken from Kaggle and modified in order to reduce computational strain on jupyter notebook. (The file is 1.6 GB and can be downloaded directly from Kaggle)
* The target variable for the model is the numeric variable interest rate.
* The data cleaning phase of the project removes all null values from the project and creates dummy variables for categorical variables.
* The featured scaling technique used in this project is normalization.
* The data split for the model was 85% training and 15% test.
* The regression method used is Least Squares.


# [Project 2: Neural Network and Logistic Regression (Employee Attrition)](https://github.com/jlugo3059/Employee-Attrition)

The primary objective of this project is to evaluate and compare the accuracy results of both a neural network and a logistic regression model using an employee attrition dataset. Likewise, the primary objective of both models in this project is to predict the binary outcome of attrition, which can either be 'yes' or 'no'. This variable determines whether an employee will continue working in their current job or not. 

* The dataset was taken from Kaggle and is available for download from both the Kaggle website and the repository files.
* The target variable is Attrition a binary variable of yes or no.
* The dataset contained no null values but did need the creation of dummy variables.
* The featured scaling technique used in this project was standardization.
* Data split for both models was 80% training and 20% test.
* The neural network used the activation function "relu" and the optimizer "adam".
* The logistic regression used an optimization algorithm called "liblinear" or "lbfgs" from scikit learn.
* For model comparisons both models calculated accuracy scores.

