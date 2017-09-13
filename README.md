# PIMA Diabetes Prediction
Using Pima Indians diabetes data set to predict whether a patient has diabetes or not based upon patient’s lab test result variables like Glucose, Blood Pressure, etc. using CART decision tree algorithm and K-Nearest Model achieving 76% accuracy.
Python-Scikit Learn, SciPy, Pandas, MatPlotLib.

Problem Statement: Diabetes is one of the deadliest diseases in the world. It is not only a disease but also creator of different kinds of diseases like heart attack, blindness etc. The normal identifying process is that patients need to visit a diagnostic center, consult their doctor, and sit tight for a day or more to get their reports.
So, the objective of this project is to identify whether the patient has diabetes or not based on diagnostic measurements.
Dataset Used: The dataset used has been obtained from UCI Machine Learning Repository having 769 records of Female Patients exclusively.

Dataset Link: https://archive.ics.uci.edu/ml/datasets/Pima+Indians+Diabetes

From the domain knowledge, I have analyzed and found out the ranges of values and its effects on diabetes for each continuous variable in the dataset. Based upon these ranges we will categorize the continuous variables for implementing the decision tree in the next step. Also, we can utilize these ranges to come up with appropriate null value replacement for each independent variable.
There are 8 independent variables:
1. Pregnancies: No. of times pregnant
2. Glucose: Plasma Glucose Concentration a 2 hour in an oral glucose tolerance test (mg/dl)
  A 2-hour value between 140 and 200 mg/dL (7.8 and 11.1 mmol/L) is called impaired glucose tolerance. This is called "pre-     diabetes." It means you are at increased risk of developing diabetes over time. A glucose level of 200 mg/dL (11.1 mmol/L)     or higher is used to diagnose diabetes.
3. Blood Pressure: Diastolic Blood Pressure(mmHg): 
  If Diastolic B.P > 90 means High B.P (High Probability of Diabetes)
  Diastolic B.P < 60 means low B.P (Less Probability of Diabetes)
4. Skin Thickness: Triceps Skin Fold Thickness (mm) –
  A value used to estimate body fat. Normal Triceps SkinFold Thickness in women is 23mm. Higher thickness leads to obesity and    chances of diabetes increases.
5. Insulin: 2-Hour Serum Insulin (mu U/ml)
 Normal Insulin Level 16-166 mIU/L
 Values above this range can be alarming.  
6. BMI: Body Mass Index (weight in kg/ height in m2)
Body Mass Index of 18.5 to 25 is within the normal range
BMI between 25 and 30 then it falls within the overweight range. A BMI of 30 or over falls within the obese range.
7. Diabetes Pedigree Function: It provides information about diabetes history in relatives and genetic relationship of those relatives with patients. Higher Pedigree Function means patient is more likely to have diabetes.
8. Age (years)
9. Outcome: Class Variable (0 or 1) where ‘0’ denotes patient is not having diabetes and ‘1’ denotes patient having diabetes
The dependent variable is whether the patient is having diabetes or not.

Data Cleaning will take place as data has got lot of missing values. Handling missing values can be done either by replacing null values with mode or mean or replacing the null value with a random variable.


Algorithms Used: As we have to classify the data into patients having diabetes or not, the best method which can be used is Classification and Regression Tree Algorithm(CART), because in this, the dataset is divided into training and testing data. Further we can easily classify and predict the outcome using nodes and internodes.

Software Package Used: Python-Scikit Learn, Numpy, Scipy, Matplotlib

Advantage of this project: The rules derived will be helpful for doctors to identify patients suffering from diabetes. Further predicting the disease early leads to treating the patient before it becomes critical.
