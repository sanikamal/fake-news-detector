# Fake News Detector
![Fake News](image/fakenews.png)

## Overview
Over the recent years, the growth of online social media has greatly facilitated the way people communicate with each other. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable. Our project aims to use Natural Language Processing to detect fake news directly, based on the text content of news articles.


## Problem Definition
Develop a machine learning program to identify when an article might be fake news. We aim to use a corpus of labeled real and fake news articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news.

## Dataset Description

**train.csv:** A full training dataset with the following attributes:
        id: unique id for a news article
        title: the title of a news article
        author: author of the news article
        text: the text of the article; could be incomplete
        label: a label that marks the article as potentially unreliable
            1: unreliable
            0: reliable

**test.csv:** A testing training dataset with all the same attributes at train.csv without the label.

## Contents

- Text pre-processing techniques
- NLP Techniques ( TF-iDF, Bag-of-words)
- Logistic Regression
- Evaluation metrics and confusion matrix
- Model Deployment using Flask.

## Try It Out

    Clone the repo to your local machine-
    > git clone https://github.com/sanikamal/fake-news-detector.git
    > cd fake-news-detector

    Make sure you have all the dependencies installed-

    python 3.6+
    numpy
    pandas
    matplotlib
    sklearn
    nltk

## Comparing Accuracies of Models

| Model         | Accuracy       |
|:-------------:|:-------------: |
|Logistic Regression | 72.94%    |
| MultinomialNB     | 88.42%     |
## Confusion Matrices

## References
- [Fake News Detection Project live session of  utsav aggarwal
](https://www.youtube.com/watch?v=xyq-zYr1cnI)
- [Datasets from Kaggle](https://www.kaggle.com/c/fake-news/overview)