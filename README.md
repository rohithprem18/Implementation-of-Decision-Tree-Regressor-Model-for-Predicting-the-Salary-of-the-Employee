# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import pandas

2.Import Decision tree classifier

3.Fit the data in the model

4.Find the accuracy score 

## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: ROHITH PREM S
RegisterNumber: 212223040172
import pandas as pd
data=pd.read_csv("/content/Salary.csv")
data.head()
data.info()
data.isnull().sum()
from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
data["Position"]=le.fit_transform(data["Position"])
data.head()
x=data[["Position","Level"]]
x.head()
y=data["Salary"]
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=2)
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=2)
from sklearn import metrics
mse=metrics.mean_squared_error(y_test,y_pred) 
mse
r2=metrics.r2_score(y_test,y_pred)
r2
dt.predict([[5,6]])

*/
```

## Output:
#### data.head()
![Screenshot 2024-04-06 114035](https://github.com/rohithprem18/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/146315115/69666c35-6fac-4e88-8d42-0119bdb0ce89)

#### data.info()
![Screenshot 2024-04-06 114043](https://github.com/rohithprem18/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/146315115/2de5b878-0b66-42c0-bac7-cb3a9b6fba0d)

#### isnull() and sum()
![Screenshot 2024-04-06 114047](https://github.com/rohithprem18/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/146315115/19e992d1-f22c-4492-a088-760d25dc607f)

#### data.head() for salary 
![Screenshot 2024-04-06 114051](https://github.com/rohithprem18/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/146315115/17415255-3f43-4983-8cd6-337e31da5153)

#### MSE value
![Screenshot 2024-04-06 114055](https://github.com/rohithprem18/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/146315115/8e9b12d9-c5a6-4608-ab3a-eea15dc71a74)

#### r2 value
![Screenshot 2024-04-06 114058](https://github.com/rohithprem18/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/146315115/798096c3-f0a1-4a08-8643-68ed09c7d2e0)

#### data prediction
![Screenshot 2024-04-06 114103](https://github.com/rohithprem18/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/146315115/7c815154-c5c4-423a-b089-c2aed30ab908)


## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
