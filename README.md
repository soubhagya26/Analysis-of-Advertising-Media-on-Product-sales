# Analysis-of-Advertising-Media-on-Product-sales
# Project Overview
## Objective : To predict sales for given budget spend on TV, Radio and Newspaper in dollars.
- Regression Problem
- Data cleaning and Data preprocessing
- Exploratory Data Analysis
- Multiple Linear Regression model training and prediction
- Statistical Analysis done from coefficients, p value, R² and Adj. R² value and F-statistic
# About Project
Machine Learning Regression model is developed to predict sales based on budgesting spends on various platforms for marketing adn advertising.The features are TV, Radio and Newspaper marketing spend in thousands of dollars.

# Code and Resources used
- Python version: 3.7.6

- Packages: Pandas, Numpy, Seaborn, Matplotlib, Scikit and Statsmodels.
# Web Scraping
- Dataset URL: https://www.kaggle.com/ashydv/advertising-dataset/notebooks
## Data fields
#### Features:

- TV: advertising dollars spent on TV for a single product in a given market (in thousands of dollars)
- Radio: advertising dollars spent on Radio
- Newspaper: advertising dollars spent on Newspaper
#### Target:

- Sales budget in thousands of dollars
## Data Cleaning
There is no missing values in data.
## EDA
I looked at the distributions of the data and the value counts for the various numerical features. Below are a few highlights :
![image](https://user-images.githubusercontent.com/98471328/188300447-655d68d7-7f7f-4fe5-b9e8-0b9ed67bbd6a.png)
## Model Building
### Multiple Linear Regression
Simple linear regression can easily be extended to include multiple features. This is called multiple linear regression:

y=β0+β1x1+…+βnxn

Each x represents a different feature, and each feature has its own coefficient. In this case:

y=β0+β1×TV+β2×Radio+β3×Newspaper

#### Advantages:
- widely used
- runs fast
- easy to use (not a lot of tuning required)
- highly interpretable
- basis for many other methods
## Model Prediction
![image](https://user-images.githubusercontent.com/98471328/188300537-9204a58b-245e-4918-8bbf-fdee195b09e5.png)
## Conclusion
To summarise, we have performed a multiple linear regression and have covered some basic introductory statistics as well. This is by no means a comprehensive analysis of the marketing data set but simply an example of how to perform and interpret a mulitple linear regression. It’s a good starting point, especially when attempting to understand the relevance of important statistical concepts like t-statistic, p-value and standard error.


