# Wine Quality Prediction with Text and Non-text Data
This project is adapted from a homework I did with one of my classmates (Bo Jumrustanasan) on the course COMS 4995 Applied Machine Learning by Dr. Andreas C. Müller at Columbia University. The aim is to predict the wine points in a [wine review dataset](https://www.kaggle.com/zynicide/wine-reviews). The project includes the following parts:

1. data visualization
2. data preprocessing and imputation using pipelines
3. grid search on Linear Regression, Elastic Net, and LinearSVR to build a baseline linear model
4. modeling with text features using Bag of Words (BoW) and word-embedding

The final model is a Linear Regression model with BoW and word-embedding. The test accuracy is 77%.