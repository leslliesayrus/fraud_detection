# Fraud_Detection

It's was developed four models of Machine Learning to detect frauds in credit card transactions. 
The dataset used from Kaggle: https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud

This dataset contain 1000000 samples, the target feature is the column 'fraud'
In the fraud column: 0 = normal transactions and 1 = frauds transactions
The data is so unbalanced, there's only 87000 exaples of frauds of 1000000.

The Smote method was applied to balance the data.

I splited the data in 70% for train and 30% for test.

The models developed was:

KNN - 
Logistic Regression - 
Decision Tree - 
Naive Bayers 

The KNN and Decision Tree was the best models with excellent predictions 

There's two insights extracted from exploratory analysis to help about fraud problem:
- The majority of frauds transactions don't use the Pin Number 
- The median distance from last transaction in fraud transactions is 3 times more than normal transactions

So that can be used to identify if a transactions is fraud or not and the Pin Number can be used to raise security in transactions
