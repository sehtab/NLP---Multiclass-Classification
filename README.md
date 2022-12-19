# NLP---Multiclass-Classification

All the discussion are in this link

https://colab.research.google.com/drive/10O9cMqMfv8VIbIMElhe7r1Z72FXpMBRo?usp=sharing 

# Objective:

The objective of this ICP is to multiclass classification. Process the words with stemming, N-gram, word-count and classify the document.

# Approaches

At first, necessary libraries are imported. The dataset is uploaded then tokenized and splitted. After split, trainset data is synthethized with word vector, and PCA analysis is done. Then word level tf-idf, character tf-idf,hashing vectorizing is done over train dataset. Then train datset is analyzed with different classifier: Naive Bayes Theorem, Linear classification, SVC with different kernel, Ada-boost classifier and Bagging classifier. All classifiers accuracy, precision, recall and F1 score is evaluated.

# Datasets

For this ICP from bbc-text.txt is used as dataset.

# Results:

Results are generated from nltk library function and sklearn they are working good. I am getting maximum accuracy from SVC classifier which is of 97% for word level tf-idf

# Challenges

Sometimes precsion, recall, f1 score show same value. For that case, for general function of precision, recall and f1 score average= 'weighted' solved the problem.

# Planned Work

bbc=text.txt attached with the colab file.Then several tf-idf for classification and featureset is being created. After splitting the dataset in train and test with 20% in test set classifiers are implemented and classifiers are performance are evaluated through Accuracy, Recall, Precision and F1 -score.
