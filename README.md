# CreditCardFraudDetection
Credit card fraud is the most common form of identity theft, affecting more than 10.7 million people annually. The key objective of any credit card fraud detection system is to identify suspicious events and report them to an analyst while letting normal transactions be automatically processed.


About Dataset:
This data set is uploaded in order to get the insights of Credit card Defaultees based on the respective attributes.Dataset contains 307510 rows and 122 columns including target columns. Here our aim is to clean the dataset and find some good insight from it.


Exploratory Data Analysis
As the dataset is too large, we divide the dataset into 3 part (object,integer,float) based on its datatype and analyze it.

After the EDA, I have built 3 baseline classification models and compared which model gives better accuracy.
1. Logistic Regression
2. K-Nearest Classifier
3. Decision Tree

Conclusion
On the Credit Card Fraud Detection, we applied three main algorithms which are to calculate, compare and evaluate different results obtained based on confusion matrix, accuracy, sensitivity, precision, AUC to identify the best machine learning algorithm that are precise, reliable and find the higher accuracy. After an accurate comparison between our models, we found that Logistic Regression achieved a higher efficiency of 92.04% and Random Forest classifier with accuracy of 92.01% outperforming decision tree.
Here we selected the top 10 features of the data set which plays a significant role in the credit card fraud detection and applied these algothims. For these 10 features, accuracy of the 3 algoriths are same and decision tree increases it accuracy from 83% to 92% with feature selection. But remaining two algorithms maintains the same accuracy for both the data sets.
