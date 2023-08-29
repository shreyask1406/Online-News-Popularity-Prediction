# Online-News-Popularity-Prediction

## Introduction
As traditional media transitions to the online realm, it becomes vital for news channels to predict the potential success of articles in the digital space. This project aims to construct predictive models that harness data mining techniques to analyze features impacting an article's popularity. Machine learning algorithms will be applied to forecast the number of shares and to classify articles as popular or not.

## Data Source
The project uses a dataset obtained from the UCI Machine Learning Repository, consisting of statistics from articles published by Mashable. The dataset contains 39797 records and 61 attributes, including predictive, non-predictive, and target variables such as the number of shares.

## Problem Definition
The project focuses on predicting the popularity of online news articles, considering shares as an indicator. The assumption is that factors like the quality of an article, reader affinity, and current events do not significantly impact an article's popularity. The primary questions addressed are:
* What attributes contribute to article popularity?
* What are the key predictors influencing shares?
* Which models perform best in predicting and classifying article popularity?

## Data Description and Cleaning
The dataset is rich in attributes that can influence article popularity. Features like the length of the article, title, keyword statistics, publication channel, and day of the week are explored. Sentiment analysis and feature engineering are also performed on textual data, generating additional predictors.

## Models Implemented
* Linear Regression: A regression model to predict the number of shares an article may receive.
* Logistic Regression: Used for classification to predict whether an article will be popular or not.
* Gaussian Naive Bayes: A probabilistic classifier for article popularity prediction.
* Support Vector Machine (SVM): A powerful algorithm for classification tasks.
* Neural Networks: Two models with different complexities to predict article popularity.

## Performance Evaluation
Performance is evaluated based on different metrics for each model:
* Regression Models (Linear Regression): Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) scores.
* Classification Models (Logistic Regression, Naive Bayes, SVM, Neural Networks): Accuracy scores.

## Key Insights
The dataset was meticulously cleaned, outliers were handled, and features were engineered.
Different models were applied, with Naive Bayes achieving the highest accuracy of 90.60% in classification.
Feature selection through Lasso Regression yielded improved results for several models.
Neural Network complexity did not lead to significant performance gains, highlighting the balance between complexity and results.

## Conclusion
This project demonstrates the application of various machine learning models in predicting online news article popularity. The models' performances varied, with Gaussian Naive Bayes excelling in classification tasks. By using predictive models, news outlets and social media platforms can anticipate the popularity of articles, optimizing content strategy and engagement.
