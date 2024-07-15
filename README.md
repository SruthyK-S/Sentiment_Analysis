# Sentiment_Analysis

## Project Overview<br>
This project aims to perform sentiment analysis on textual data using machine learning techniques. Sentiment analysis involves determining the sentiment expressed in text, which can be positive, negative, or neutral. In this project, we utilize TF-IDF Vectorization for text processing and the Support Vector Classifier (SVC) from the scikit-learn library for model training and sentiment analysis.

## Introduction
The project employs TF-IDF Vectorization to assign weights to words based on their importance in documents. This method captures the significance of words within reviews more effectively than Count Vectorization, which merely counts word occurrences. Additionally, the Support Vector Classifier (SVC) is used for model training and sentiment analysis. SVC can handle high-dimensional data efficiently and is particularly well-suited for text classification tasks where the feature space can be vast.

## Data Processing
The data processing step involves:

* Loading the raw data.
* Cleaning the text data (removing stop words, punctuation, etc.).
* Vectorizing the text data using TF-IDF Vectorization.

## Model Training
The model training step involves:

* Splitting the data into training and testing sets.
* Training the Support Vector Classifier (SVC) using the training data.
* Saving the trained model for future use.
