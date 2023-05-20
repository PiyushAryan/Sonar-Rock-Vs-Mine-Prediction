# Sonar Rock vs Mine Prediction using Logistic Regression Model

This repository contains code and data for building a logistic regression model to predict whether a sonar signal represents a rock or a mine.

**# Requirements** 

To run the code in this repository, you will need the following:

Python 3.6.x-3.11

scikit-learn

NumPy

Pandas

Matplotlib


**# Getting Started**

Clone this repository to any Juypter Notebook (most preferable : Google Colabaratory).
run the Jupyter notebook main.ipynb.
Run each cell in the notebook to reproduce the analysis.
```
**📌 Do add the Sonar_data.csv in content section of juypter notebook ( Google Colab)**
```
**# Data**

The dataset used in this project consists of 200+ sonar signals, each of which is either a rock or a mine. Each signal has 60 features, which are the energy values at different frequencies. 

**# Analysis**

In this project, we build a logistic regression model using scikit-learn's LogisticRegression class. We train the model on the training set and evaluate its performance on the test set.Calculate the AUC score to measure the model's performance.

**# Conclusion**

The logistic regression model achieves an accuracy of 76.13% on the test set, and AUC score is 73% indicating that it is able to predict whether a sonar signal represents a rock or a mine with reasonable accuracy. However, there may be opportunities to improve the model's performance through feature engineering or using a different classification algorithm.

