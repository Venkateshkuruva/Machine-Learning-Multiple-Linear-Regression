

# Investment Prediction using Linear Regression

This project focuses on building a Linear Regression model to predict investment amounts based on various business and financial features. It uses both scikit-learn for model building and statsmodels for statistical analysis of the predictors.


🧠 Objective
To understand the relationship between company or financial data and investment amounts, and to:

Build a predictive model using Linear Regression

Evaluate feature importance using OLS (Ordinary Least Squares) analysis

Prepare the dataset using dummy encoding for categorical variables

📁 Dataset
The dataset used in this project is assumed to contain business-related information and corresponding investment values.


🔧 Tools & Libraries
Python

NumPy

Pandas

Matplotlib

scikit-learn

statsmodels


🛠️ Workflow
Data Loading
Load the dataset using pandas.

Feature Selection
Separate independent (X) and dependent (y) variables. Dummy encode categorical features.

Train-Test Split
Use train_test_split from scikit-learn to divide data into training and testing sets.

Model Training
Fit a Linear Regression model using LinearRegression().

Prediction
Predict investment values on test data and compare with actuals.

Model Evaluation
Print regression coefficients and intercept.

OLS Analysis
Use statsmodels to assess the statistical significance of predictors using OLS.

📈 Output
Regression coefficients and intercept from scikit-learn

Full statistical summary from OLS regression

Option to visualize predictions and residuals (can be added)






