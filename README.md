# -Credit Card Fraud Detection Using The Machine Learning

# Problem statement:-
The aim of the project is to predict fraudulent credit card transactions using machine learning models. This is crucial from the bank’s as well as customer’s perspective. The banks cannot afford to lose their customers’ money to fraudsters. Every fraud is a loss to the bank as the bank is responsible for the fraud transactions.

The dataset contains transactions made over a period of two days in September 2013 by European credit cardholders. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. We need to take care of the data imbalance while building the model and come up with the best model by trying various algorithms.

# Business Problem Overview
For many banks, retaining high profitable customers is the number one business goal. Banking fraud, however, poses a significant threat to this goal for different banks. In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

# Main challenges involved in credit card fraud detection are:
1-Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time.
2-Imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones
3-Data availability as the data is mostly private.
4-Misclassified Data can be another major issue, as not every fraudulent transaction is caught and reported.
5-Adaptive techniques used against the model by the scammers.

# How to tackle these challenges?

1-The model used must be simple and fast enough to detect the anomaly and classify it as a fraudulent transaction as quickly as possible.
2- Imbalance can be dealt with by properly using some methods like oversampling and undersampling but we used ensemble methods , It handle imbalanced data.
3-A more trustworthy source must be taken which double-check the data, at least for training the model.
4-We can make the model simple and interpretable so that when the scammer adapts to it with just some tweaks we can have a new model up and running to deploy.

# Dataset:
Click this DataSet Link 👉 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
The data set includes credit card transactions made by European cardholders over a period of two days in September 2013. Out of a total of 2,84,807 transactions, 492 were fraudulent. This data set is highly unbalanced, with the positive class (frauds) accounting for 0.172% of the total transactions. The data set has also been modified with Principal Component Analysis (PCA) to maintain confidentiality. Apart from ‘time’ and ‘amount’, all the other features (V1, V2, V3, up to V28) are the principal components obtained using PCA. The feature 'time' contains the seconds elapsed between the first transaction in the data set and the subsequent transactions. The feature 'amount' is the transaction amount. The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.



# Project Pipeline
1- Import lib
2- Import data
3- Data analysis & Visualization
4- Data Preprocessing
5- Train & Evaluate models



 
