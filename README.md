# Job Salary For Data Science
* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 

## Model performance
try linear model lasso and ridge give score 70 % train and 65 % test
*Notice that the best model is RandomForestRegressor that gives training score 96 % and testing score 80 %
