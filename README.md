# Student-Grade-Prediction-Using-Multiple-Linear-Regression
Problem Statement
Predicting the final exam grade for secondary students given their attributes such as student grades, demographic, social, and school-related features. This helps the school management to group students and give them tailored learning exercises to improve their final exam grades.

Dataset
The data contains 33 variables and of which G3 (grade for final exam) is the Target variable. The complete data dictionary can be found here.

 
Build Regression Models in Python for House Price Prediction
Tasks
Find top 3 highly correlated numerical and categorical features with the target variable.

Numerical Features (using correlation)

Categorical Features (How do you find the correlation between categorical vs. numerical variables ?)

How do you check outliers in each column? Create a function that takes in each column and caps the value in the Inter Quartile Range (effectively removing outliers).

Analyze the below hypotheses and find insights.

Does a parent's job have any impact on the final grade?

Does travel time & study time affect the final grade?

Impact of Internet access at home on the final grade

Is there any multi-collinearity among the features? If so, how do you find and remove those variables? (Hint: VIF)

Create new features based on the EDA

Build Regression models to predict the final exam grade 

Compare the test RMSE/MAE between Linear regression vs. Ridge/Lasso regression to understand the importance of regularization and how it affects the model generalization.

 

Build regression models and compare their performance to understand the importance of regularization.

 

FAQs
Q1. What are the top 3 highly correlated numerical features with the target variable?

The top 3 highly correlated numerical features with the target variable can be determined using correlation analysis.

 

Q2. How can the correlation between categorical and numerical variables be found?

To find the correlation between categorical and numerical variables, techniques such as ANOVA or chi-square tests can be employed.

 

Q3. How do you check outliers in each column and remove them?

Outliers in each column can be checked by calculating the interquartile range (IQR) and using it to cap values outside a certain range. A function can be created for this purpose.
