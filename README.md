# Credit-Card-Fraud-Detection
# Problem statement
The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning models.

In this project, we will analyse customer-level data which has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group.

The dataset is taken from the Kaggle Website and it has a total of 2,84,807 transactions, out of which 492 are fraudulent. Since the dataset is highly imbalanced, so it needs to be handled before model building.
# Facts about data

 * The dataset is highly imbalanced, the positive class (frauds) account for 0.172% of all transactions.
* Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 
* The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. 
* Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
![coorelation matrix](https://user-images.githubusercontent.com/118895788/203995246-815b7df2-0115-4df4-8cd2-d8b2801a0c8d.PNG)

# Data Dictionary
The dataset can be download using this [link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)


The data set includes credit card transactions made by European cardholders over a period of two days in September 2013. Out of a total of 2,84,807 transactions, 492 were fraudulent. This data set is highly unbalanced, with the positive class (frauds) accounting for 0.172% of the total transactions. The data set has also been modified with Principal Component Analysis (PCA) to maintain confidentiality. Apart from ‘time’ and ‘amount’, all the other features (V1, V2, V3, up to V28) are the principal components obtained using PCA. The feature 'time' contains the seconds elapsed between the first transaction in the data set and the subsequent transactions. The feature 'amount' is the transaction amount. The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.

# Life cycle of the project
* Data scraping
* Data cleaning
* Processing on data 
* Model creation

# Motivation and purpose of the project
As we know fraud trasaction can cause penulties to the customers that they did not purchase so this model will help to know the fraud transactions. 
