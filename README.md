## Title
Random Forest Classifier for Employees Turnover Prediction

## Overview
The goal of this project was to create a classifier and random forest model to predict whether an employee is at risk of leaving a company or not. This project utilized employees data from a fictitions company called Salifort Motors. The final random forest model achieved an AUC of 96.5%, a recall of 87% and a precision of 86%, finding what features best determined the conditions that would produce employee turnover for Salifort Motors. The model also outperformerd moderately the other models that was tested during the modeling process. (Logistic Regression, Decision Trees). Based on the model, last evaluation, number of projects, tenure and whether an employee was overworked, were the most influential featues in determining if and employee is staying or leaving the company.


## Business Understanding
As part of the good practices within Human Resources (HR) most companies conduct performances and satisfaction surveys periodically during the fiscal year. Senior leadership often take actionable strategies based on the insights discovered from these surveys. One of the most common goal is to analyze the data to come up with ideas for increasing employee retention. As its commomly known that recruiting, hiring, onboarding, and upskilling new employees have a inherent cost whether in time or economically.  With the goal of avoiding such cost from these processes, companies leverage these surveys to be able to could build a model that is designed to predict whether an employee will leave the company based on their department, number of projects, average monthly hours, and any other data points its deem helpful.

[Insert Stats and Research to justify the business proposal]

## Data Understanding


## Modeling and Evaluation
A random forest model comprising 500 decision trees was used to determine feature importance in which employees would leave or stay. The below plot shows that last evaluation, number of projects, tenure, and the fact whether an employee was overworked or not were among the Top 4 most important factors in determining a employee leaving or staying. The overall model performed with 89.8% recall, 87.1% precision and an AUC of 93.5%. 

[Image]


## Conclusion
