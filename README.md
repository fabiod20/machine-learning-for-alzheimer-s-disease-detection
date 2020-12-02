# Machine learning for Alzheimer's Disease Detection
This repository contains the solution proposed for the first Mini-Contest of the **Data Mining** course of *University of Naples Federico II* (https://www.kaggle.com/c/unina-data-mining-2021-minicontest-n1/overview).

The contest aims at exploiting Machine Learning for Alzheimer's disease detection. The task is to determine whether a patient has or not the disease, by means of a machine learning model trained on some medical high-level information.

The solution shown in the Notebook, implemented by means of *scikit-learn*, is made up of two main stages:
- **Preprocessing**: data cleaning and dealing with missing values.
- **Modeling**: several models have been compared for our purpose, such as *decision tree*, *k-nearest neighbour*, *logistic regression* and *multi layer perceptron*, but the best one turned out to be *support vector machine*.
