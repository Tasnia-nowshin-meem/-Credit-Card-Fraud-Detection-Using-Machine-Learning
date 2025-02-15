# -Credit-Card-Fraud-Detection-Using-Machine-Learning

# ABSTRACT

Credit card fraud is a significant problem, with billions of dollars lost each year. Machine learning can be used to detect credit card fraud by identifying patterns that are indicative of fraudulent transactions. Credit card fraud refers to the physical loss of a credit card or the loss of sensitive credit card information. Many machinelearning algorithms can be used for detection. This project proposes to develop a machine-learning model to detect credit card fraud. The model will be trained on a dataset of historical credit card transactions and evaluated on a holdout dataset of unseen transactions.

# Data Source

The dataset was retrieved from an open-source website, Kaggle.com. It contains data on transactions made in 2013 by European credit card users in two days only. Thedataset consists of 31 attributes and 284,808 rows. Twenty-eight attributes are numeric variables that, due to the confidentiality and privacy of the customers, have been transformed using PCA transformation; the three remaining attributes are ”Time”, which contains the elapsed seconds between the first and other transactions of each Attribute, ”Amount” is the amount of each transaction, and the final attribute “Class” which contains binary variableswhere “1” is a case of fraudulent transaction, and “0” is not as case of fraudulent transaction.

Dataset:  https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# Machine Learning Algorithms Used
#Logistic Regression
The method of modelling the probability of a discrete result given an input variable is known as logistic regression. The most frequent logistic regression models have a binary outcome, which might be true or false, yes or no, and so forth. Logistic regression is a handy analysis tool for determining if a fresh sample fits best into a category in classification tasks. Because components of cyber security, such as threat detection, are classification problems, logistic regression is a valuable analytic tool.

![image](https://github.com/user-attachments/assets/82934bae-2c17-48eb-8ba8-349f72216481)

# Random Forest

Random Forest is an ensemble algorithm that combines multiple decision trees to make predictions. Each decision tree is trained on a random subset of features and samples from the dataset. In credit card fraud detection, Random Forest can capture complex relationships between features and effectively handle imbalanced datasets. By aggregating the predictions of individual trees, the model provides a robust and accurate fraud detection mechanism.

