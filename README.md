# Spam Email Detection Project

Spam Email Detection is a project focused on building an effective machine learning model that can discern between spam and non-spam (ham) emails. This model leverages Natural Language Processing (NLP) techniques and utilizes Support Vector Machines (SVM) to achieve its goal. By representing email texts using the TF-IDF (Term Frequency-Inverse Document Frequency) technique, the SVM classifier can make accurate predictions based on vectorized features.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Training](#model-training)
5. [Evaluation Metrics](#evaluation-metrics)
6. [Authors](#authors)

## Introduction

Spam Email Detection is a project that aims to build a machine learning model capable of distinguishing between spam and non-spam (ham) emails using Natural Language Processing (NLP) techniques and Support Vector Machines (SVM). The model utilizes the TF-IDF (Term Frequency-Inverse Document Frequency) representation to convert email texts into numerical vectors, enabling the SVM classifier to make predictions based on these vectorized features.

## Dataset

The dataset used for training and evaluating the model is stored in the file `spam_or_not_spam.csv`. It contains a collection of email texts along with their corresponding labels, where 1 represents spam emails and 0 represents non-spam emails.

## Data Preprocessing

In this phase, we perform various data preprocessing steps to clean and prepare the email data for training the model. The steps include:

- Converting all email texts to lowercase for consistency.
- Replacing email addresses, URLs, currency symbols, phone numbers, and numeric characters with placeholders.
- Removing punctuation, extra white spaces, and common stopwords.
- Creating additional features like email length and cleaned email length.

## Model Training

The model training process involves the following steps:

- Converting email texts into numerical vectors using the TF-IDF representation.
- Splitting the dataset into training and testing sets.
- Training an SVM classifier on the training data.

## Evaluation Metrics

To assess the performance of the model, we use several evaluation metrics, including:

- Accuracy: The percentage of correct predictions over the total number of predictions.
- Precision: The ratio of true positive predictions to the total positive predictions made by the model.
- Recall: The ratio of true positive predictions to the total actual positive instances in the dataset.
- F1-Score: The harmonic mean of precision and recall, providing a balanced measure of the model's performance.

## Authors

- [@galudSla](https://github.com/galudSla)
- email: tedgiann@gmail.com
