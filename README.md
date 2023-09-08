# Salifort_Motors
Data analysis of Salifort Motors project (part of Google Advanced Data Analytics Certification)
This project is completed as a part of the Google Advanced Data Analytics Capstone Project.
It utilizes data analytics concepts and techniques covered in the professional certification course.

## Overview
Salifort Motors is a fictitious company created for educational purposes only.
Salifort Motors has over 10,000 employees and the data of the employees has been shared in the notebook.
The company is facing an issue where many of their employees are resigning from the company.
This is forcing the company to hire more employees thereby increasing their financial expenditures on hiring, screening and the overall process.
The HR department has requested an analysis of the causes for employees leaving and probable solutions to increase retention
and employee satisfaction. I am required to also recommend business solutions to the financial issue.

## Objectives
-Determine cause of employees resigning
-Build a prediction model to predict if an employee will leave
-Recommend solutions to the problem with results of analysis

## Analysis
A PACE strategy document was formulated to initiate the process and workflow.
An initial exploratory data analysis was conducted and it was noticed that employees were overworked.
A machine learning model was built to determine if an employee would leave using different methods such as Random Forest Classification,
Logistic Regression, Extreme Gradient Boosting and Decision Tree Classifier.

## Results
The results of the analysis were as follows:
-A large portion of the employees were overworked
-Employees were working on multiple projects at the same time
-Employees were not promoted
-Employees who have worked for many years had very low satisfaction levels
-A majority of the salaries of employees were in the lower bracket

## Solutions
Proposed solutions are as follows :
-Reduce the number of working hours on an average
-Reduce the number of projects each employee is tasked to handle
-Increase the number of holidays for employees
-Increase the number of promotions
-Add perks/benefits to long-serving employees
-Improve work culture

Further solutions and analysis can be made with additional data of the employees. The data faced an issue with class imbalance which can be
improved with upsampling of data.

The results of the models are shown in the jupyter notebook, a brief overview of the scores of each model is given below :
|           name	          |  accuracy	| precision	| recall	  |  f1	      | roc_auc
| decision_tree_classifier	| 0.977498	| 0.952119	| 0.912292	| 0.931734	| 0.973615
| logistic_regression	      | 0.825425	| 0.464286	| 0.242021	| 0.318182	| 0.592754
| random_forest_classifier	| 0.979848	| 0.963795	| 0.914973	| 0.938675	| 0.980638
| xgb_classifier	0.976414	| 0.955143	| 0.902576	| 0.928037	| 0.973586  | 0.974143

## Libraries Used
-numpy
-pandas
-sklearn
-xgboost
-matplotlib
-seaborn
