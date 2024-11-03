## Title
Random Forest Classifier for Employees Turnover Prediction

## Overview
The goal of this project was to create a classifier and random forest model to predict whether an employee is at risk of leaving a company or not. This project utilized employees data from a fictitions company called Salifort Motors. The final random forest model achieved an AUC of 96%, a recall of 93% and a precision of 97%, finding what features best determined the conditions that would produce employee turnover for Salifort Motors. The model also outperformerd moderately the other models that was tested during the modeling process. (Logistic Regression, Decision Trees). Based on the model, last evaluation, number of projects, tenure and whether an employee was overworked, were the most influential featues in determining if and employee is staying or leaving the company.

## Business Understanding
As part of the good practices within Human Resources (HR) most companies conduct performances and satisfaction surveys periodically during the fiscal year. Senior leadership often take actionable strategies based on the insights discovered from these surveys. One of the most common goal is to analyze the data to come up with ideas for increasing employee retention. As its commomly known that recruiting, hiring, onboarding, and upskilling new employees have a inherent cost whether in time or economically.  With the goal of avoiding such cost from these processes, companies leverage these surveys to be able to could build a model that is designed to predict whether an employee will leave the company based on their department, number of projects, average monthly hours, and any other data points its deem helpful.

<img src="images/Employee%20Turnover%20Cost%20by%20Industry.png" width="500">

**Source:** *O'Connell, Matthew & Kung, Mavis (Mei-Chuan). (2007). The Cost of Employee Turnover.. Industrial Management. 49. 14-19.*

## Data Understanding
The dataset is originally from kaggle, it contains information from a fictitious company named Salifort Motors regarding their last employees last employees self-reported survey. The data consisted of approximately 14999 unique self-reported responses and 10 features. The features included information on satisfaction level, last evaluation performance, number of project employee contributes to, average monthly hours, time spend in the company, and other valuable information. The bar chart below shows the breakdown of how many employees that stayed and left exist in the dataset.

<img src="images/Target%20Count%20Plot.png" width="500">

## Modeling and Evaluation
A random forest model comprising 300 decision trees was used to determine feature importance in which employees would leave or stay. The below plot shows that `last evaluation`, `number of projects`, `tenure`, and the fact whether an employee was `overworked` or not were among the top 4 most important factors in determining a employee leaving or staying. The overall model performed with **92.6% recall**, **97.2% precision** and an **AUC of 96%**. 

<img src="images/Feature%20Importance.png" width="600">

## Conclusion

The models and features importances reviewed from the models confirm that employees within Salifort Motors are overworked.
To retain employees, the following recomendations could be presented to the stakeholders:
- Limit the number of projects that employees can work on.
- Prioritize promotion for employees that have been with the company at least 4 years.
- Choose between rewarding accordingly employees who work longer hours or don't require them to do so.
- High evaluation for performance review should be attribute to every employee who contribute more/put in more effort and not only for employees who worke 200+ hours per month.
- Next steps could be, to try to limit features that may not be available at all times for the model to perform well, like last evaluation performance or satisfaction level.
