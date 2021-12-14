


![App Screenshot](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRRUarc9vSLuD3GgTIpoCrbDzNILO5xxvDO6w&usqp=CAU)




## Inrtoduction
The world encountered its first corona virus case on December 31, 2019 in china.People all around the world in a state of confusion and fear started sharing their concerns on twitter.We are given a dataset with the information of tweets all around the world.


 


## Problem statement

We are tasked with predicting the sentiment of the tweets data which has been pulled from twitter.This is a supervised ml classification problem.
Our model helps understand the sentiment behind a particular tweet and build a sentiment prediction algorithm around it.





## Overview of the data
We are given the following columns in our data:
1. Location  -  name of the location from which the tweet was shared.
2. TweetAt  -  time of the tweet at which the tweet was shared.  
3. OriginalTweet  -  the original tweet shared by the user.
4. UserName  -  identification given by twitter to the user.
5. ScreenName  -  name projected on the screen of the user.
6. Sentiment  -  defined sentiment or label from the shared tweet.


## Steps involved
1. Installing libraies and getting the dataset.
2. Performing EDA (exploratory data analysis).
3. Drawing conclusions from the data.
4. Preprocessing the data.
5. Training different models.
6. Evaluating metrics of all the models.

## Algorithms used
1. Logistic Regression
2. Decision Trees Classifier
3. Multinomial Naive bayes classifier

## Models used
1. Word Counts with CountVectorizer:
- The CountVectorizer provides a simple way to both tokenize a collection of text documents and build a vocabulary of known words, but also to encode new documents using that vocabulary.
- An encoded vector is returned with a length of the entire vocabulary and an integer count for the number of times each word appeared in the document.
2. Tf-IDF method:
- TF-IDF (term frequency-inverse document frequency) is a statistical measure that evaluates how relevant a word is to a document in a collection of documents, which is done by multiplying two metrics: how many times a word appears in a document, and the inverse document frequency of the word across a set of documents.
- It has many uses, most importantly in automated text analysis, and is very useful for scoring words in machine learning algorithms for Natural Language Processing (NLP).
## Conclussion
We have used different metrics here such as accuracy score, precision score, recall score and f1-score.

The scores of all the models on test set are:
1. Logisic Regression- 
- Accuracy score:  0.8033
- Precision score:  0.8046
- Recall score:  0.8033
- F1-score:  0.8038
2. Decision Trees Classifier-
- Accuracy score:  0.5017
- Precision score: 0.4613  
- Recall score:  0.9626
- F1-score:  0.6265
3. Multinomial Naive bayes classifier-
- Accuracy score:  0.6856
- Precision score:   0.7348
- Recall score:  0.7249
- F1-score:  0.7215
