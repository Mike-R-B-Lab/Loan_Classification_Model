# Loan Default Prediciton (MIT Certificate Final Project)


## Problem Statement

The consumer credit department of a bank contacted us (hypothetically) to simplify their decision-making process by implementing a machine learning model capable of predicting loan defaults using 13 features for 5960 of their past borrowers. In the past, they had a 20% default rate on their loans.

I proceeded by using different analytical techniques to visualize and examine the provided data. These were the steps taken : 

    1. Data Overview
    2. Exploratory Data Analysis (EDA) and Visualization
        - Univariate Analysis
        - Bivariate Analysis
        - Replacing missing values
        - Multivariate Analysis (K-means)
        - Treating outliers
    3. Model Building
        - Data preparation
        - Logistic Regression 
        - Decision Tree
        - Random Forest


We found that the key features that determine whether a person is likely to default on a loan are the number of missing values in their application, the duration of their longest credit line and the number of delinquent credit lines they have.

The most effective model overall was the Tuned Random Forest while using an 80-20 split for the training and testing data.

The code used to arrive to these findings can be found in the Google Colab Notebook.



