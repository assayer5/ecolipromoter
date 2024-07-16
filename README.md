# Project: E. coli Promoter Sequence Classification

### Overview
Classified E. coli sequences as promoter or non-promoter using k-mer counting on the UCI Machine Learning Repository: Molecular Biology (Promoter Gene Sequences) Data Set.
Naive bayes classifier and logistic regression yielded similar results in 5-fold cross validation and test set accuracy.

### Some Details
With the UCI Machine Learning Repository: Molecular Biology (Promoter Gene Sequences) dataset, I classified short sequences (57 bases long) as either a promoter sequence or non-promoter sequence. After engineering some features from the sequence data, I tested two models for classification: Naive bayes and logistic regression.

>*promoter_seq_classif.ipynb*
>
>To classify the sequences as either 'promoter' or 'non-promoter', I needed to engineer features from the sequences. I calculated the GC content of each sequence and created k-mers of size=6. With the k-mers, I created bag of words model for the classifiers. Although I tested two models, both had high training and testing accuracy. I plotted precision , recall, and ROC curves for completeness.

### Language
Python

### Packages Used
numpy, pandas, sklearn

### Model
- Multinomial Naive Bayes Classifier
- Logistic Regression with L2 Regularization

### Resources
[Kaggle](https://www.kaggle.com/)

[UCI Machine Learning Repository: Molecular Biology (Promoter Gene Sequences) Data Set](https://archive.ics.uci.edu/ml/datasets/Molecular+Biology+%28Promoter+Gene+Sequences%29\
)
