# Tweet Sentiment Analysis Using Naive Bayes (NB) and Logistic regression (LR)

This slef -project implements Tweet Sentiment Analysis using Logistic Regression and Naive Bayes classifiers to determine the sentiment of tweets (positive, negative, or neutral). The goal is to predict whether a tweet expresses a positive, negative, or neutral sentiment based on the text content.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)
- [Sources](#license)

## Introduction

In this project, we use Natural Language Processing (NLP) techniques to build and train sentiment analysis models on a tweet dataset. Sentiment analysis is the process of determining the emotional tone behind a series of words, and in this case, we focus on tweets.

## Dataset

The dataset used for this project can be found at nltk twitter data 10k records. It consists of labeled tweets, where each tweet is labeled as positive, negative, or neutral sentiment. The dataset is preprocessed to remove noise, special characters, and irrelevant information.

## Models

We have implemented two different models for sentiment analysis:

1. Logistic Regression: A simple linear model that learns to classify tweets into positive, negative, or neutral sentiments based on features extracted from the text.
2. Naive Bayes: A probabilistic model that makes predictions based on the Bayes theorem. Despite its simplicity, Naive Bayes can be surprisingly effective for sentiment analysis tasks.

## Results

The performance of the models was evaluated using accuracy, precision, recall, and F1-score metrics. The results of the evaluation are as follows:

- Logistic Regression:
  - Accuracy: 0.9950
- Naive Bayes:
  - Accuracy: 0.9955
- both model performs equally onthis dataset
- 80:20 split dataset for train-test.

## Sources
- Foundation of ML (CS725)
- Deep learning for NLP (CS772)
- Coursera - NLP specilization
