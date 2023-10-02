# Sentiment Analysis of Tweets

The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

# **Extracting Features from Cleaned Tweets**
To analyze preprocessed data, it needs to be converted into features.
Feature Extraction has been done through 3 models respectively:
* Bag Of Words (BOW)
* TF-IDF Model
* Word2Vec Model

# **Model Building**

We are now done with all the pre-modelling stages required to get the data in the proper form and shape. We will be building models on the datasets with different feature sets prepared in the earlier sections —
* Bag-of-Words
* TF-IDF
* Word2Vec vectors

We will use the Logistic Regression algorithms to build model

**Evaluation Metric**

Following Evaluation Metrics are being used:
* F1 Score
* Accuracy Score
* ROC-AUC Score

**NOTE: ** The results and the metrics are not very good due thr huge data imbalance present in the data set, it must be taken care for before training the model
