# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>Import pandas as pd and from sklearn import linear_model

### Step2
<br>Read the csv file from the drive

### Step3
<br>Drive the required list from the file

### Step4
<br>Print the list of the program

### Step5
<br>End the program

## Program:
```
#Implementation of Multivariate Linear Regression
#Developed By: M.Krithika Lakshmi
#Register NUmber: 212224230134

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("/content/car (1).csv")
x=df[["Volume","Weight"]]
y=df["CO2"]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))


```
## Output:

### Insert your output

![alt text](<Screenshot 2025-05-22 100010.png>)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.