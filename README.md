# Sampling Assignment


This assignment aims to identify the best sampling technique for a highly imbalanced dataset by comparing the performance of seven different machine learning models.

Dataset

The dataset used in this project is Credit Card Fraud Detection dataset, which is highly imbalanced, with the majority class accounting for 95% of the samples. To address this issue, the Synthetic Minority Over-sampling Technique (SMOTE) was used to generate synthetic samples for the minority class.

## Sampling Techniques

Four different sampling techniques were used to generate samples from the imbalanced dataset:

- Simple Random Sampling
- Stratified Sampling
- Systematic Sampling
- Cluster Sampling
- Machine Learning Models

Six different machine learning models were used to classify the samples:

- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- Support Vector Machine
- Gaussian Naive Bayes

## Results

The performance of each model was evaluated using metrics such as accuracy, precision, recall, and F1-score. The Random Forest Classifier was found to be the best model with the highest accuracy.


| MODEL NAME             | Random Sampling | Systematic Sampling | Stratified Sampling | Cluster Sampling |
|------------------------|-----------------|---------------------|---------------------|------------------|
| RandomForestClassifier | 1.00            | 1.00                | 0.99                | 0.98             |
| DecisionTreeClassifier | 0.97            | 0.99                | 0.98                | 0.97             |
| LogisticRegression     | 0.94            | 0.97                | 0.94                | 0.97             |
| GaussianNB             | 0.92            | 0.91                | 0.91                | 0.94             |
| SVC                    | 0.77            | 0.84                | 0.82                | 0.86             |
| KNeighborsClassifier   | 0.74            | 0.74                | 0.74                | 0.75             |


## Conclusion

Based on the results, the use of SMOTE to balance the dataset, combined with the Random Forest Classifier, can improve the performance of machine learning models on imbalanced datasets. Further research can be conducted on other sampling techniques and machine learning models to achieve better results.
