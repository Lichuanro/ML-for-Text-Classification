# Machine Learning techniques for Text Classification
 
This repository will contain common ML techniques for text classification.

In text classification, we are given a document and a fixed set of classes. Classes are also called categories or labels. Our goal is to design algorithms or build models to map documents to classes.

The dataset is part of ["The 20 newsgroups text dataset"](http://qwone.com/~jason/20Newsgroups/), the words are splited and counted for easy experiments in text applications of machine learning techniques.

## Methods of text classification
* Hand-coded rule-based classifiers
* Supervised learning
    * [Naive Bayes](https://github.com/Lichuanro/ML-for-Text-Classification/blob/master/Naive%20Bayes.ipynb) (simple, common)
    * [k-Nearest Neighbors](https://github.com/Lichuanro/ML-for-Text-Classification/blob/master/kNN.ipynb) (simple, powerful)
    * Support-vector machines (newer, generally more powerful)
    * [Decision trees](https://github.com/Lichuanro/ML-for-Text-Classification/blob/master/Decision%20Tree.ipynb) -> random forests -> gradient-boosted decision trees (e.g., xgboost)
    * Deep Learning
        * Multi Layer Perceptron (MLP)
        * Convolutional Neural Networks (CNN)
        * Recurrent Neural Networks (RNN)
