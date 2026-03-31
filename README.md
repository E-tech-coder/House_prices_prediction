# House_prices_prediction
🏠 House Prices - Exploratory Data Analysis

This project performs Exploratory Data Analysis (EDA) on the Ames Housing dataset from Kaggle, aiming to uncover key factors that influence house prices and prepare the data for predictive modeling.

📊 Project Overview
Dataset: Ames Housing Dataset
Goal: Understand the structure of the data and identify features that impact house prices
Tech Stack: Python, Pandas, NumPy, Matplotlib, Seaborn

📁 Dataset Description
1460 observations
81 columns
79 explanatory variables
1 target variable: SalePrice
1 ID column
Feature Types:
🔢 Numerical features: 36
🔤 Categorical features: 43

🔍 Key Steps
1. Problem Definition
Understanding how different housing features influence the final sale price.
2. Data Cleaning
Identified missing values across multiple columns
Handled categorical missing values by assigning "Missing"
Avoided dropping high-missing columns to preserve information
3. Data Understanding
Separated categorical and numerical variables
Analyzed dataset structure and distributions
4. Exploratory Data Analysis (EDA)
Investigated relationships between features and SalePrice
Explored categorical feature distributions
Identified potentially important predictors

📈 Key Insights
Features like overall quality, living area, and location-related variables strongly influence price
Missing values in some features may carry meaningful information rather than noise
Categorical variables play a significant role and require careful encoding

🚀 Future Work
Feature engineering
Encoding categorical variables
Building regression models:
Linear Regression
Random Forest
Gradient Boosting (e.g., XGBoost)
Model evaluation and optimization

📎 References
Kaggle Competition: House Prices - Advanced Regression Techniques
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

👤 Author
Elena Chen 
Aspiring Data Scientist | Background in ERP Consulting
