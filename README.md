# SafeSwipe: Detecting Credit Card Fraud
Vidal, Marlon, and Steve

## Objective
Evaluate the ability of 3 supervised Machine Learning models to detect fraudulent credit card transactions against a dataset of 284k transactions. We selected the Random Forest, Logistic Regression, and Gaussian Naive Bayes models.

## Summary of Findings
The Random Forest and Gaussian Naive Bayes models with the severely imbalanced dataset ~400 fraudulent transactions out of 284k certainly had room for improvement when it came to detecting the minority class successfully. While the Logistic Regression model implied the use of a balanced dataset, that resulted in better performance.

After utilizing the SMOTE method to oversample our minority fraudulent transactions, both the Random Forest and Gaussian Naive Bayes models outpeformed the initial runs. The Random Forest model performed the best, delivering a 99.99% recall for fraudulent transactions and 99.95% recall for legitimate ones.

This outcome emphasizes the important of having balanced datasets in classification problems.
