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

# Life cycle of the project
* Data scraping
* Data cleaning
* Processing on data 
* Model creation

# Motivation and purpose of the project
As we know fraud trasaction can cause penulties to the customers that they did not purchase so this model will help to know the fraud transactions. 
