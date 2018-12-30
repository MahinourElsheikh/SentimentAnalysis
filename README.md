# Sentiment Analysis
NLP task : postive or negative Review Sentiment Analyzer using IMDB dataset in Python .
## Overview
1. Dataset

    The 100K reviews are divided into three datasets: 25K labeled training instances, 25K labeled test instances and 50K unlabeled training instances. Each review has one label representing the sentiment of it: Positive or Negative. These labels are balanced in both the training and the test set.

2. Text Pre-processing

    Text preprocessing was done in order to remove unecessary words or turn verbs and adjectives into a unified word to make the model less confused . Text PreProcessing included
     + spell checker
     + stop words removal (is,are,the,this ....etc)
     + Lemmatization

3. Vector Spaces and Data Matrix

    This step aimed to convert the text of the review after pre-processing into a vector form for
    further steps.Different alternatives  for text representation inclued:
     + n-grams.
     + Count, TF-IDF.
     + DocToVec

4. Supervised Learning Step

   We tried multiple of classification models. We tuned their parameters. We tuned ​these models parameters on 10% subset of the training set. 
   Model choices are:
    * Decision Trees
    * Random Forests
    * SVM Non-Linear
    * Adaboost
    * Logistic Regression
    * Bagging
>>

