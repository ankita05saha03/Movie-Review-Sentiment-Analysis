# Movie-Review-Sentiment-Analysis

This project focuses on analyzing the sentiment of movie reviews. The goal is to determine whether a given review is positive or negative based on its text content. This can be useful for understanding general sentiment about a movie and for improving recommendation systems.

# Dataset: 
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

# Overview

The Movie Review Sentiment Analysis project uses Natural Language Processing (NLP) techniques to classify movie reviews as either positive or negative. The project includes data preprocessing, feature extraction, model training, and evaluation steps.

# Models and Techniques
The project employs various NLP techniques and machine learning models, including:

* Text Preprocessing: Tokenization, stopword removal, and Lemmatization.
* Feature Extraction: TF-IDF Vectorizer.
* Machine Learning Model: Naive Bayes Classifier.

# Results

The performance of the Naive Bayes model with the best parameters ({'alpha': 1.0, 'fit_prior': False}) is as follows:

* Best Cross-Validation Score: 0.86165
* Test Accuracy: 0.8674
* Mean Cross-Validated Accuracy: 0.86165
* Standard Deviation of Cross-Validated Accuracy: 0.00152970585407784

These results demonstrate that the Naive Bayes model performs consistently well with an overall accuracy of approximately 86.74% on the test set. The precision, recall, and F1-score are balanced across both positive and negative classes, indicating that the model is effective at distinguishing between positive and negative movie reviews.
