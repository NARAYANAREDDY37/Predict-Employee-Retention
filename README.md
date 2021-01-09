# About Predict-Employee-Retention project 

Predict Employee Retention is an end to end machine learning project. The main task of the project is to build machine learning model for HR management that can predict the employee retention within the organization. So, In this project I have taken previous data of some employees which includes important factors like satisfaction level, average time spent in the company, no of projects worked on etc,. that effect the churning rate of employees. 

## Steps Involved
•	Imported necessary libraries and dependencies and visualized different plots to understand more about data

•	Checked correlation by viewing heatmap and pair plot to see multiple pairwise bivariate distributions

•	Handled categorical data using statistical methods and separated the data into train and test

•	Used grid search CV for hyper parameter tuning and exposed the data to Xgboost algorithm 

•	Created flask app and and exposed it as REST API to retrain and predict new set of data in future

•	Created REST API and UI page to predict the result for single record from screen 

•	Deployed the model in amazon AWS EC2 with Nginx, Guinicorn and Supervisor

