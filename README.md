# Sentiment Analysis
NLP task : postive or negative Review Sentiment Analyzer using IMDB dataset in Python .
## Overview
1. ***Dataset***

    The 100K reviews are divided into three datasets: 25K labeled training instances, 25K labeled test instances and 50K unlabeled training instances. Each review has one label representing the sentiment of it: Positive or Negative. These labels are balanced in both the training and the test set.

2. ***Text Pre-processing***

    Text preprocessing was done in order to remove unecessary words or turn verbs and adjectives into a unified word to make the model less confused . Text PreProcessing included
     + spell checker
     + stop words removal (is,are,the,this ....etc)
     + Lemmatization


3. ***Vector Spaces and Data Matrix***

    This step aimed to convert the text of the review after pre-processing into a vector form for
    further steps.Different alternatives  for text representation inclued:
     + n-grams.
     + Count, TF-IDF.
     + DocToVec


4. ***Supervised Learning Step***

   We tried multiple of classification models. We tuned their parameters. We tuned ​these models parameters on 10% subset of the training set. 
   Model choices are:
    * Decision Trees
    * Random Forests
    * SVM Non-Linear
    * Adaboost
    * Logistic Regression
    * Bagging


5. ***Results***

   With All mentioned Preprocessing:

   + Logistic regression :87.5%,
   + Adaboost 80% 
   + Decision trees was 52% before turning and reached 70% after 

   With preprocessing without lemmatization:
 
    + Random forests was 54% before tuning and reached  85.5% after 
    + Adaboost 79.852%

   Without preprocessing at all expept html removal:

    + Naive Bayes 85.4%
    + Logistic Regression 88.6% with c set to 1000
    + Adaboost 80.2%
    +  Random Forests was 83.6% before tuning and 86.6% after

   With stop words removal and html only:

    + Logistic Regression 88.3%

   Without any preprocessiong:

    + Logistic Refression 88.5%

>>

