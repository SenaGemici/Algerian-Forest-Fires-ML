The dataset was obtained from Kaggle:https://www.kaggle.com/datasets/nitinchoudhary012/algerian-forest-fires-dataset

1. Data Cleaning: missing values, column name cleanup
2. One Hot Encoding for categorical features
3. Exploratory Data Analysis (EDA)
4. Correlation analysis to reduce multicollinearity
5. Model building and comparison:
   - Linear Regression
   - Lasso
   - LassoCV
   - Ridge
   - RidgeCV
   - ElasticNet
   - ElasticNetCV

- The target variable for prediction is the Fire Weather Index (FWI).
 After comparing all models, Linear Regression gave the best performance in predicting FWI.
