# Predicting the Sale Price of Bulldozers using Machine Learning

This project aims to predict the auction sale price of heavy equipment—specifically bulldozers—to create a “blue book” that provides reliable price estimates based on historical data. The solution is implemented using **scikit-learn** for machine learning and is developed and executed in a **Jupyter Notebook** environment.

## Overview

Using data provided by the [Bluebook for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers) competition on Kaggle, this project leverages machine learning techniques to analyze and predict auction prices. The goal is to generate accurate price predictions that can be used to assess equipment value in the heavy machinery market.

## Dataset Description

The dataset comprises three main files:

- **Train.csv**: Contains the training data up to the end of 2011. This file is used to train the model.
- **Test.csv**: Contains data from May 1, 2012, to November 2012. This set is held back and released at the end of the competition. Your performance on this set determines the final ranking.
- **Valid.csv**: Contains data from January 1, 2012, to April 30, 2012. Predictions on this set are used to generate the public leaderboard throughout the competition.

Kaggle also provides a comprehensive data dictionary detailing all features in the dataset, including auction details, equipment characteristics, and more.

## Evaluation Metric

The performance of the predictive model is evaluated using the **Root Mean Squared Logarithmic Error (RMSLE)**.
