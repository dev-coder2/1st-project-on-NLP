# Spam Classification Using NLP Techniques

This project demonstrates spam classification using various Natural Language Processing (NLP) techniques, including **Bag of Words (BoW)**, **TF-IDF**, **Word2Vec**, and **AvgWord2Vec**. The goal is to predict whether a message is spam or not based on these different feature extraction methods and evaluate their performance in terms of accuracy.

## Techniques Used:
- **Bag of Words (BoW)**: A simple model where each message is represented as a vector of word frequencies.
- **TF-IDF (Term Frequency-Inverse Document Frequency)**: A more advanced technique that helps capture the importance of words in a document relative to the entire corpus.
- **Word2Vec**: A deep learning technique that transforms words into dense vector representations based on context.
- **AvgWord2Vec**: An aggregation of word vectors where the vector for a sentence/document is the average of the vectors for the individual words in it.

## Features:
- Preprocessing of the dataset (tokenization, stop word removal, etc.)
- Implementation of BoW, TF-IDF, Word2Vec, and AvgWord2Vec
- Comparison of performance using different techniques
- Spam classification model training using Logistic Regression, Multinomial Naive Bayes, etc.
- Evaluation using accuracy and classification report (precision, recall, F1-score)
