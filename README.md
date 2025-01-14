# Assignment 4: Understanding LSTMs with Sentiment Analysis

## Overview

This repository presents a comprehensive implementation of a sentiment analysis model using Long Short-Term Memory (LSTM) networks. Sentiment analysis plays a crucial role in understanding text data by identifying opinions, attitudes, and emotions expressed in written communication. The primary objective is to classify IMDb movie reviews as either positive or negative, providing insights into the underlying sentiments.

The project involves multiple stages, starting from data loading and preprocessing to model development, evaluation, and predictions. A balanced dataset of 10,000 reviews ensures unbiased training and testing. The preprocessing pipeline includes tokenization, lemmatization, and removal of stop words to prepare the data for modeling. Additionally, pre-trained FastText word embeddings are utilized to initialize the embedding layer, enhancing the semantic understanding of the model.

The custom LSTM model is designed with flexibility and robustness in mind, incorporating layers such as dropout, batch normalization, and a fully connected output layer. This implementation is complemented by a comparison with PyTorch's standard LSTM model to evaluate the advantages and trade-offs of each approach.

Key aspects of the project include visualizing word embeddings in reduced dimensions using PCA, exploring sentiment-rich words, and analyzing model performance through metrics like accuracy, precision, recall, and F1-score. The project also demonstrates how to handle out-of-vocabulary (OOV) words and improve model robustness.

Finally, the best-performing model is used to predict sentiments for a new dataset, and the predictions are saved in a structured format for further analysis. This end-to-end implementation showcases the process of building, training, and deploying a deep learning model for natural language processing tasks.

## Highlights of the Project
- **Dataset:** 10,000 balanced movie reviews from IMDb.
- **Preprocessing:** Tokenization, lemmatization, and stop word removal with sequence padding.
- **Model:** Custom LSTM implementation with FastText embeddings and PyTorch's LSTM for comparison.
- **Metrics:** Evaluated using accuracy, precision, recall, F1-score, and confusion matrix.
