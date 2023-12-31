# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
  Import necessary libraries (pandas, scikit-learn).
  
### Step2
  Load the dataset containing features (independent variables) and the target variable (dependent variable).

### Step3
  Separate the features (independent variables) into a matrix X and separate the target variable (dependent variable) into a vector y.

### Step4
  Instantiate a linear regression model object (e.g., using LinearRegression() from scikit-learn).  

### Step5
  Train the model by fitting it to the data using the fit() method: model.fit(X, y).
  Use the trained model to make predictions on new data: predictions = model.predict(new_data).

## Program:
```
#Multivariate Linear Regression
#Developed by: VENKATANATHAN P R
#Registration Number: 23000285

import pandas as pd
from sklearn import linear_model
df=pd.read_csv('cars.csv')
a=df[['Weight', 'Volume']]
b=df[['CO2']]
regr-linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept:", regr.intercept_)
print("Amount:", regr.predict([[3300,1300]]))
```
## Output:
![Screenshot 2023-12-31 192735](https://github.com/23000285/Multivariate-Linear-Regression/assets/138970859/f681d4df-7b10-497f-ae9f-435cfbbcc565)
![image](https://github.com/23000285/Multivariate-Linear-Regression/assets/138970859/c14deea8-1d4a-4a74-8829-492b9af4a5d2)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
