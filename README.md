# My-Portfolio

# [Project 1: Multivariable Regression (Accepted Loans)](https://github.com/jlugo3059/Multivariable-Regression)

This project focuses on doing a multivariable regression on a loan’s dataset. The loans dataset comprises data from over one million borrowers who were approved to receive loans by the Lending Club company. Employing the dataset given, the model created within this project will utilize a multivariable regression method to forecast interest rates based on the independent variables present in the data.

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

# [Project 3 : Attrition Dashboard](https://public.tableau.com/app/profile/jorge.lugo/viz/Projecttableau_16878442443360/Dashboard1?publish=yes)

This project uses the attrition dataset (same dataset from project 2) to create a dashboard on tableau.  Similarly, to the second project the primary focus is the variable attrition, (dictates whether or not an employee continues working at their current job or not) which we will be compared with other similar categorical visual.

* Note that attrition is still binary, and all the visualizations compare categorical variables as a percentage value of the total sum of attrition (in other words, they calculated how much of the categories were "yes" out of all the aggregate values of "yes" and "no”).
* Martial Status is a categorical variable of people who identified as single, married, and divorced.
* Business Travel is a categorical variable which displays individuals who identified as traveling frequently, traveling rarely, and not traveling at all as part of their jobs.
* Job roles is as its name implies, job roles that employees identified as having.
* Lastly gender are employees who identified as being male or female. Note that there is a parameter for gender which filters all the other visualizations based on specified gender. 
