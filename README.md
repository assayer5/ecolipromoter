# Project: E. coli Promoter Sequence Classification

### Overview
Classified E. coli sequences as promoter or non-promoter using k-mer counting on the UCI Machine Learning Repository: Molecular Biology (Promoter Gene Sequences) Data Set.
Naive bayes classifier and logistic regression yielded similar results in 5-fold cross validation and test set accuracy.

### Language
Python

### Packages Used
numpy, pandas, sklearn

### Feature Engineering
- created k-mers of size=5 
- created bag of words model for classifier

### Model
- Bernoulli Naive Bayes Classifier
- Logistic Regression with L2 Regularization

### Resources
[Kaggle](https://www.kaggle.com/)

[UCI Machine Learning Repository: Molecular Biology (Promoter Gene Sequences) Data Set](https://archive.ics.uci.edu/ml/datasets/Molecular+Biology+%28Promoter+Gene+Sequences%29\
)
