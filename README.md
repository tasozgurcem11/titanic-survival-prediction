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
model, and the test set is used to evaluate the model. The data is in CSV format. Columns are: (PassengerId, Survived, 
Survived, Pclass, Name, ..., Fare). The first column is the PassengerId, which is a unique identifier for each
passenger.