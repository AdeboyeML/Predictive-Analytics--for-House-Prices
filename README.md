# Advanced-Regression-Techniques-for-House-Prices

This project is geared towards predicting house prices using advanced regressor models and this was carried out through extensive data exploration with the use of advanced data visualization libraries such as Seaborn and Plotly, and the use of regularized regression models such as Ridge, Lasso, Elastic Net Regressor and Ensemble models such as RandomForest, XGBoost, Gradient Boost to predict house prices in Ames, Iowa and further engineer features that will help optimize the models performance.

**This project was executed twice using similar approaches but different data visualization libraries and machine learning models.**

## Advanced-Regression-Techniques-For-House-Prices--Part 1

This first part used Seaborn as the data visulaization library and regularized regression models such as Ridge, Lasso and Elastic Net Regressors with Decision Trees and Random Forest Regressor were used to predict the house prices based on the model with the lowest Root Mean Square Error. 


Data wrangling played a significant part in this particular project, where most of the categorical features ( if not all) were transformed into a numeric form so that they can be correlated with the target varaiable to determine how strong their relationship is with the target variable.

## Advanced-Regression-Techniques-For-House-Prices--Part 2

The second part of this project used plotly as the data visualization library and ensemble models such as Random Forest, XGBoost, Gradient Boost, ADABoost and Light GBM were all utilized to predict the house prices. Here, the models were first cross validated to have a glimpse of their performance and then grid search was done on them to find the best tuning hyperparameters, thereafter the models with the lowest RMSE were stacked together.

Feature engineering was part of the approach used in this project, as it was observed that summing up some highly correlated numeric features yield high and better correlation to the target variable.


Overall, the libraries utilized include ***pandas, numpy, seaborn, matplotlib, mxlned, sklearn and scipy.***
