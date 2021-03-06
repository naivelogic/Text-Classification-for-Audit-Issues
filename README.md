# Text-Classification-for-Audit-Issues

## Overview
In this notebook we will walkthrough solving a complete machine learning problem for classifying documents. Our objective is as follows: 

	Use the provided data, develop a model to assess and predict the classification of a given document.

To get started, first lets review the beaisc approach for developing this solution. This is a supervised machine learning task, which means we train models with trianing data long with the label associated with it. Since this is supervised learning we have already been provided the labels on the data sets. We will have to extract features from each sample, and use an algorithm to train a model where the inputs are those feature and the output is the label. 

For classifying the testing data, the classifier uses decision boundary to separate points of the data belonging to each class. In a statistical-classification problem with two classes, a decision boundary partitions all the underlying vector space into two separate classes. In this specific case we used a Support Vector Machine (SVM) which is a linear classifier which constructs a boundary by focusing two closest points from different classes and finds the line that is equidistant to these two points. 

## Dependencies
* numpy 
* matplotlib
* scikit-learn

## Usage
Just run `jupyter notebook` in terminal and it will run in you rbrowser. 
Install Jupyter [here](https://jupyter.readthedocs.io/en/latest/install.html) if you haven't yet. 



## Further Reading and References

### Natual Language Processing
* [Bag-of-words model](https://en.wikipedia.org/wiki/Bag-of-words_model)
* [Tokenization](https://en.wikipedia.org/wiki/Lexical_analysis#Tokenization)
* [TF-IDF](https://en.wikipedia.org/wiki/Tf%E2%80%93idf)


### Machine Learning Model Selection
* [Voting Ensemble](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.VotingClassifier.html)
* [Implementing Ensemble Models in Sklearn](https://machinelearningmastery.com/ensemble-machine-learning-algorithms-python-scikit-learn/)
* [AdaBoostClassifier](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html)
