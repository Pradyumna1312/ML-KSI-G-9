# ML-KSI-G-9
![image](https://user-images.githubusercontent.com/54210084/133266939-fc9780a4-6753-44c9-905d-5346be19fe73.png) ![image](https://user-images.githubusercontent.com/54210084/133267049-e87858dd-b9ea-45b2-a2f7-4b4a6764d35c.png)


# RV College of Engineering	                        	Knowledge Solutions India 

Internship Program
Course: Machine Learning &AI with Python
Batch-11
Group-9
Topic-1(Admission Prediction)






By: Narsepalli Pradyumna
RV College of Engineering
USN: 1RV19EC106

TABLE OF CONTENTS
Page no
1.	Table of content.……………………………………………………………02
2.	Table of Graphs…………………………………………………...…….…03
3.	Abstract…………………………………………………………………….10
4.	Chapters
i)	Introduction………………………………………………………….10
ii)	Software-libraries……………………………………………………10
iii)	Algorithm……………………………………………………………10
5.	Conclusion………………………………………………………………….11



















Table of Graphs
1)	GRE score vs Chance of Admit

2)	TOEFL Score vs Chance of Admit



3)	University ranking vs Chance of Admit


4)	SOP vs Chance of Admit




5)	LOR vs Chance of Admit

6)	CGPA vs Chance of Admit





7)	Research vs Chance of Admit
8)Original vs Predicted Graphs
a)	GRE score vs Chance of Admit





b)	TOEFL Score vs Chance of Admit

c)	University ranking vs Chance of Admit







d)	SOP vs Chance of Admit
 
e)	LOR vs Chance of Admit
 






f)	CGPA vs Chance of Admit
 
g)	Research vs Chance of Admit

 





Abstract
	The project is concerned about the probability of getting a seat in a prestigious university depending on scores in GRE and TOEFL exams and their LORs, SOPs and CGPAs from their previous study institutes. We made an ML Project to determine the chance of admit and predict different sets.

Chapters
1)	Introduction
Our graduate school application provides the admissions committee with a great deal of information about you that cannot be found elsewhere in your graduate application. The other parts of your graduate school application tell the admissions committee about your grades (i.e., transcript), your academic promise (i.e., GRE scores), and what your professors think of you (i.e., recommendation letters). Despite all of this information, the admissions committee does not learn much about you as an individual. Therefore, by predicting the colleges at our grasp helps us in applying to these colleges.
	This project is for this prediction i.e. the chance of admittance in a certain university. 
2)	Libraries used
1.	NumPy
2.	Pandas
3.	Matplotlib
4.	Sklearn
5.	Statsmodels

3)	Algorithm
Problem Description:
We have the dataset created for prediction of Graduate Admissions from an Indian perspective containing 500 entries.
Since we need to find the Chance of Admit, so it is the dependent variable, and the other seven variables are independent variables. Below are the main steps of deploying the MLR model:
a)	Implementation of Multiple Linear Regression model 
1.	Data Pre-processing Steps
2.	Fitting the MLR model to the training set
3.	Predicting the result of the test set
Step-1: Data Pre-processing Step:
The very first step is data pre-processing. This process contains the below steps:
o	Importing libraries: Firstly, we will import the library which will help in building the model. 
o	Importing Datasets: Now we will import the dataset (Admission_Predict_Ver1.1), which contains all the variables.
o	Extracting Dependent and Independent Variables:
o	Creating Test and Train data:
Step-2: Fitting our MLR model to the Training set
Step-3: Prediction of Test set results
a)	Implementation Steps for Random Forest Regressor
1.	Data Pre-processing step
2.	Fitting the Random forest algorithm to the Training set
3.	Predicting the test result

Conclusion
We are able to predict the colleges in our grasp with a minimum R-Squared error of 0.81637 with Random Forest Regressor and 0.829 with Multiple Linear Regression.

	
