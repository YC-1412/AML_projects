# Used Car Price Prediction with Regression Models
This project is modified from a homework I did with one of my classmates (Bo Jumrustanasan) on the course COMS 4995 Applied Machine Learning by Dr. Andreas C. Müller at Columbia University. The aim is to predict the the price of a used vehicle on craigslist ([data](https://www.kaggle.com/austinreese/craigslist-carstrucks-data)). The project includes the following parts:

1. data visualization
2. data preprocessing and imputation using pipelines
3. grid search on Linear Regression, Elastic Net, and LinearSVR to build a baseline linear model
4. feature engineering (e.g. imputation, encoding) and grid search on Random Forst and Gradient Boosting models and hyperparameters to find the best model
5. feature selection using permutation importance and auto feature selection (Random Forst)
6. build an explainable model that is nearly as good as the best model

The final model is a Gradient Boosting Regressor model. The test accuracy is 79%.