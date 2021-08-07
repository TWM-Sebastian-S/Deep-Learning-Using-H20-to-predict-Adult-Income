# Deep Learning using H2O to Predict Adult Income

### This is one of my personal DS/ML/DL projects I've been working in since I started my career as a Data Scientist.

## Project Overview

Deep Learning Project in Python created using H2O to find out the best model to predict if an adult will have an annual income of more or less of 50k.
Project included: 
  - Breakdown Problem Statement
  - EDA & database cleaning
  - Perform Univariate & bi-variate analysis for both numeric and categorical variables
  - Create models using H20
  - Perform Hyper-parameter tuning using a grid.
  - Compare the performance of different models using AUC and F1 score.


## Problem Statement

This is UCI Machine Learning Repository dataset. Extraction was done by Barry Becker from the 1994 Census database. A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0))

Prediction task is to determine whether a person makes over 50K a year.

## Code and resources used
**Python Version:** 3.7

**Packages:** Pandas / Numpy / Seaborn / H2O

**ML Resources:** Deep Learning / Neural Networks / AUC / Confusion Matrix / F1

## Model Building

H2O is a Java-based software for data modeling and general computing. The H2O software is many things, but the primary purpose of H2O is as a distributed (many machines), parallel (many CPUs), in memory (several hundred GBs Xmx) processing engine. 

For application developers and data scientists, the gritty details of thread-safety, algorithm parallelism, and node coherence on a network are concealed by simple-to-use REST calls. In addition, H2O is an open-source project under the Apache v2 licence. All of the source code is on github.

H2O uses a distributed key-value store (the “DKV”) that contains pointers to the various objects of the H2O ecosystem.

Model building in this python module is influenced by both scikit-learn and the H2O R package. A section of the documentation is devoted to discussing the way to use the existing scikit-learn software with H2O-powered algorithms.

Every model object inherits from the H2OEstimator from the h2o.estimators submodule. After an estimator has been specified and trained, it will additionally inherit methods to the following five model categories:
- Regression
- Binomial
 -Multinomial
- Clustering
- Autoencoder

## Hyperparameter Tuning

I define a grid for hyperparameter that search for the best parameters between activation, epochs and different hidden layers.

## Model Performance

According to the hyperparameters, H20 built more than 40 different models that I listed for their F1-score descending. The best model was selected with a 0,71 F1. Recall Curve](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression/blob/main/Precision%20Recall%20Curve.JPG "Precision Recall Curve")

## Conclusion

I came up with a Deep Learning neural network model using H2O to predict adult income.

[GitHub Repository](https://github.com/TWM-Sebastian-S/Deep-Learning-Using-H20-to-predict-Adult-Income)
