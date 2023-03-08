# Mini-project IV

### [Assignment](assignment.md)

## Project/Goals
To bulid a loan estimator model for deployment. This project is elping us predict if loans should be provided or not.

## Hypothesis
• Salary: Applicant with high income should have more chances of loan approval.

• Previous History: Applicant who have repaid their previous debts should have higher chances of loan approval.

• Loan Amount: Loan Approval should also depend on the loan amount. If the loan amount is less, chances of loan approval should be high.

• Loan Term: Loan for less time and less amount should have higher chances of approval.

• Property Area: Properties in urban areas have higher growth perspectives and increment in valuation of the property.

## EDA 
Had to check the dependency of variable on loan status(target). Made multiple charts and plots to understand the distribution of data.


## Process
(fill in what you did during EDA, cleaning, feature engineering, modeling, deployment, testing)
### EDA: Had to check the dependency of variable on loan status(target). Made multiple charts and plots to understand the distribution of data. Filled in missing values through median and mode. 
### Made few more features to explore te data and dependency. Divided the data into train and test datasets to build logistic regression, random forest, and decision tree model. Tuned hypermeters to get better accuracy

## Results/Demo
(fill in your model's performance, details about the API you created, and (optional) a link to an live demo)

## Challanges 
Deployment of model through flask and writing JSON code for prediction

## Future Goals
Build another model with XGboost with better results
(what would you do if you had more time? are there any potential issues/biases with your model/use case?)
