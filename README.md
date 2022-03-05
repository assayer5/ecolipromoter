# Project: E. coli Promoter Sequence Classification

### Overview
Classified E. coli sequences as promoter or non-promoter using k-mer counting and a naive bayes classifier on the UCI Machine Learning Repository: Molecular Biology (Promoter Gene Sequences) Data Set.
Final model scored a mean accuracy of 0.9125 with 5-fold cross validation and an accuracy of 0.9259 on the test set.

### Language
Python

### Packages Used
numpy, pandas, sklearn

### Feature Engineering
- created k-mers of size=5 
- created bag of words model for classifier

### Model
Bernoulli Naive Bayes Classifier

### Resources
[Kaggle](https://www.kaggle.com/)
[UCI Machine Learning Repository: Molecular Biology (Promoter Gene Sequences) Data Set](https://archive.ics.uci.edu/ml/datasets/Molecular+Biology+%28Promoter+Gene+Sequences%29\
)
