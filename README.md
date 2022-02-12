# Titanic survival prediction with machine learning classifiers.


### Contents

1. [Introduction](#introduction) 
2. [Data](#data)
3. [Data preprocessing](#data-preprocessing)
4. [Model](#model)
5. [Evaluation](#evaluation)
6. [Conclusion](#conclusion)
7. [References](#references)

***

### Introduction

This dataset is a subset of the [Titanic dataset](https://www.kaggle.com/c/titanic) which is a large dataset of 
passengers on the Titanic. The Titanic is the world's largest passenger liner, and was supposed to ship around
2,200 people. It sank in the North Atlantic Ocean in 1912. We miss the Titanic, but we can still learn a lot.

This problem is a classification problem. The goal is to predict whether a passenger survived the sinking of the Titanic.

To visualize model 
`brew install graphviz`


### Data

Data is provided in the [Kaggle Titanic competition](https://www.kaggle.com/c/titanic). You can download and unzip the
data. It consists of a training set of 891 entries and a test set of 418 entries. The training set is used to train the
model, and the test set is used to evaluate the model. The data is in CSV format.

Columns are: (PassengerId, Survived, Survived, Pclass, Name, ..., Fare)

The first column is the PassengerId, which is a unique identifier for each
passenger.


### Data preprocessing

Data preprocessing is the process of converting the data into a form that is suitable for training a machine
learning model. Basically, we need to convert the data into a form that is suitable for the model.


### Model

There are many machine learning models that can be used to predict the outcome of a problem. In this project we will 
use a simple model called a decision tree. The decision tree is a tree-based model that can be used to predict the 
survival of a passenger. 

Used models:
* [Decision tree](http://scikit-learn.org/stable/modules/tree.html)
* [Random forest](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
* [Gradient boosting](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)
* [AdaBoost](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html)
* [xgboost](http://xgboost.readthedocs.io/en/latest/model.html)
* [LightGBM](https://lightgbm.readthedocs.io/en/latest/index.html)
* [Perceptron](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Perceptron.html)


### Evaluation

Evaluation is the process of determining the accuracy of a model. The accuracy is the fraction of the predictions. 
Cross-validation is a technique that is used to determine the accuracy of a model. Confusion matrix is used to get
better understanding of the model evaluation. Different evaulation scores are:

F1 score: F1 score is a measure of the effectiveness of a classification model. It is the harmonic mean of precision.
Precision: Precision is a measure of the model's positive prediction. It is the fraction of the true positives.
Recall: Recall is a measure of the model's true positive prediction. It is the fraction of the true positives.
Accuracy: Accuracy is the fraction of the correct predictions.