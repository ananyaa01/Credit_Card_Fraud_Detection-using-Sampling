# Credit_Card_Fraud_Detection_using_Sampling
The challenge is to recognize fraudulent credit card transactions so that the customers of credit card companies are not charged for items that they did not purchase.

Main challenges involved in credit card fraud detection are:

1-Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time.

2-Imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones
3-Data availability as the data is mostly private.

# Getting Started

- Importing the required libraries

- Loading the dataset

- Checking for the balanced or imbalanced dataset

<img align="centre" src="https://github.com/ananyaa01/Credit_Card_Fraud_Detection-using-Sampling/blob/2968ce6bda4657ae910e86f0511f118ad24fa9ba/Screenshot%202023-02-20%20at%201.14.02%20AM.png" height="550" />

- As we see that the dataset is highly imbalanced , so we need to do resampling.

## Applying SMOTE to do oversampling

- SMOTE (Synthetic Minority Over-Sampling Technique), which is a combination of oversampling and undersampling, but the oversampling approach is not by replicating minority class but constructing new minority class data instance via an algorithm.


# Next Step : Applying Different Sampling Techniques 

- Random Sampling
- Systematic Sampling
- Stratified Sampling
- Cluster Sampling
- Reservoir Sampling

## Applying Different models on all 5 samples and comparing the Accuracies


|         | Random   | Systematic  | Stratified | Cluster | Reservoir |
| :---: | :---: | :---: |:---: | :---: |:---: |
| Grid Search | 0.875 |	0.937 |	0.854 |	0.953 |	0.886  |
| Naive Bayes | 0.621 |	0.937 |	0.725 |	0.886 |	0.73 |
| Logistic Regression | 0.86| 0.911 |	0.849 |	0.917 |	0.87 |
| Random Forest | 0.99481 |	0.994 |	0.994 |	0.994 |	0.994 |
| Decision Tree | 0.917	| 0.917	| 0.922 |	0.979	 | 0.932 |




# Results:

- Ramdom Forest Classifier gives best accuracy on all types of sampling.

## Submitted By:

- Ananya Agarwal
- Roll No: 102017085






