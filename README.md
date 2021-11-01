# HeartDisease

The project of predicting heart disease for elder people(65+) based on multiple factor using machine learning.
As given in heart.csv(source:https://www.kaggle.com/ronitf/heart-disease-uci/version/1) file the factors in each column which responsible for heart disease in elder people.
1.age
2.sex
3.chest pain type (4 values)
4.resting blood pressure
5.serum cholestoral in mg/dl
6.fasting blood sugar > 120 mg/dl
7.resting electrocardiographic results (values 0,1,2)
8.maximum heart rate achieved
9.exercise induced angina
10.oldpeak = ST depression induced by exercise relative to rest
11.the slope of the peak exercise ST segment
12.number of major vessels (0-3) colored by flourosopy
13.thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

By using logistic regression on data with 80% training sets and 20% testing sets we will achive target.
here target is 0 and 1.
where 1-> person having heart disease.
      0-> person not have any disease.


Steps for running code:

1. intall python compiler like jupyter notebook.
2. Now copy the code given in heart.py
3. paste the path of heart.csv in " heart_data=pd.read_csv('/content/heart.csv') ".
4. now execute.
5. considering sunita sharma age is 65 so following are her attributes:
age: 65
sex: 1
chest pain type (4 values): 3
resting blood pressure: 145
serum cholestoral in mg/dl: 233
fasting blood sugar > 120 mg/dl: 1
resting electrocardiographic results (values 0,1,2): 0
maximum heart rate achieved: 150
exercise induced angina: 0
oldpeak = ST depression induced by exercise relative to rest: 2
the slope of the peak exercise ST segment: 3
number of major vessels (0-3) colored by flourosopy: 0
thal: 3 = normal; 6 = fixed defect; 7 = reversable defect: 0

which in result she have heart disease.
