# Fraudulent credit card transactions
## Analyzing different machine learning algorithms to find the most suitable taking into account that data is probably highly imbalanced

Credit card fraud is a term that has been coined for unauthorized access of payment cards like credit cards or debit cards to pay for 
using services or goods. Hackers or fraudsters may obtain the confidential details of the card from unsecured websites. When a fraudster
compromises an individuals creditdebit card, everyone involved in the process suffers, right from the individual whose confidential data 
has been leaked to the businesses generally banks who issue the credit card and the merchant who is finalizing the transaction with purchase.
 
 The dataset used for this project was taken from Kaggle and can be found: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
 
## Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Content
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
