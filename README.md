# HeartDisease

On of the major problems our elder face are Heart problems.

This is a project for predicting heart disease for elder people(65+) based on multiple factor using machine learning.

As given in heart.csv(source:https://www.kaggle.com/ronitf/heart-disease-uci/version/1) file the factors in each column which responsible for heart disease in 65+ people.

 let sunita sharma age 65 have to test whether she have heart disease or not
 
age: 65
sex: 1
chest pain type (4 values):3
resting blood pressure:145
serum cholestoral in mg/dl:233
fasting blood sugar > 120 mg/dl: 1
resting electrocardiographic results (values 0,1,2): 0
maximum heart rate achieved: 150
exercise induced angina: 0
oldpeak = ST depression induced by exercise relative to rest: 2
the slope of the peak exercise ST segment: 3
number of major vessels (0-3) colored by flourosopy: 0
thal: 3 = normal; 6 = fixed defect; 7 = reversable defect:0

After performing logistic regression it results

" You have a heart disease please contact your doctor. "

By using logistic regression on given data with 80% training sets and 20% testing we will achive target.
Here target is 0 and 1.
where 1-> person having heart disease.
      0-> person not have any disease.
 
 steps to run this file:
  >install python compiler like jupyter notebook
  >paste the link of heart.csv in " heart_data=pd.read_csv('/content/heart.csv') ".
  >paste 65,1,3,145,233,1,0,150,0,2.3,0,0,1 in  " input_data=(65,1,3,145,233,1,0,150,0,2.3,0,0,1) ".
  >run all it will give target output.
      
       


