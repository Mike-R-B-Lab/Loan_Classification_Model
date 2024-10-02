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

### Investment simulation 

For our dataset, 1,189 defaulted loans means $23,903,656 lost (1,189 defaulted * 20,104 average dollars lost/defaulted loans).

The average repaid loan was 19,028 dollars, which means that over a 5-year period with a 7% interest rate paid monthly, the bank would make 6,638 dollars per repaid loan.

There were 4,771 repaid loans meaning that the bank earned 31,669,898 dollars.

Total profit = $31,669,898 - $23,903,656 = $7,766,242

If we had implemented the model prior to all these applicants

Number of defaulted loans = (100% - 73%) * 1,189 = 321
Dollars lost = 321 x $20,104 = $6,453,384

Number repaid loans lost = (100% - 94%) * 4,771 = 287
Profit lost = 287 x $6,638 = 1,905,106

Cost of web application = 200k (high security)

Cost of data analytics consultant = 5k

Total profit = $31,669,898 - ($6,453,384 + $1,905,106 + $200,000 + $5,000) = $23,106,408

If the bank had used our classification model, they would have had an extra $15,340,166 in profit.

The code used to arrive to these findings can be found in the Notebook.



