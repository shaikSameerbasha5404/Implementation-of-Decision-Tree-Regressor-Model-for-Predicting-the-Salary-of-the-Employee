# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import pandas
2. Import Decision tree classifier
3. Fit the data in the model
4. Find the accuracy score

## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: Shaik Sameer Basha
RegisterNumber: 212222240093
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
![7 1](https://github.com/shaikSameerbasha5404/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/118707756/fa2e5371-0d4a-48e6-9234-3ea281941efe)

#### data.info()
![7 2](https://github.com/shaikSameerbasha5404/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/118707756/cbe5546d-6630-4319-8ccf-0f17f682dd39)

#### isnull() and sum()
![7 3](https://github.com/shaikSameerbasha5404/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/118707756/27ffd4b4-92db-455f-bbff-4f252aadf71c)

#### data.head() for salary 
![7 4](https://github.com/shaikSameerbasha5404/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/118707756/b033a8bc-d0c2-44ae-b590-efaa0b65417b)

#### MSE value
![7 5](https://github.com/shaikSameerbasha5404/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/118707756/c8679939-1f73-4d3f-a144-1cb5619e7cf5)

#### r2 value
![7 6](https://github.com/shaikSameerbasha5404/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/118707756/f89f4894-a236-4142-ba87-84eacaa7e303)

#### data prediction
![7 7](https://github.com/shaikSameerbasha5404/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/118707756/0e423334-5481-4720-b3f2-ed894d739a84)

 
## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
