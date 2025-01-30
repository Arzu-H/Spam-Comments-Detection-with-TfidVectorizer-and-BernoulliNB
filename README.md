# Spam Comments Detection

This project builds a machine learning model to classify YouTube comments as **Spam** or **Not Spam** using natural language processing (NLP) techniques.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Overview](#model-overview)
- [Evaluation](#evaluation)
- [License](#license)

## Introduction
This notebook aims to detect spam comments using a dataset containing YouTube comments. The approach involves:
- Data exploration (EDA)
- Text preprocessing
- Model training using a Naïve Bayes classifier
- Performance evaluation

## Dataset
The dataset used is `Youtube.csv`, which contains:
- **CONTENT_az**: The text of the comment.
- **CLASS**: Binary label where `0` means Not Spam and `1` means Spam.

## Installation
To run this notebook, install the required dependencies:
```bash
pip install pandas seaborn scikit-learn matplotlib
```

## Usage
1. Load the dataset and explore it.
2. Preprocess the text data.
3. Train the model using the Bernoulli Naïve Bayes classifier.
4. Evaluate the model's performance.

Run the Jupyter Notebook:
```bash
jupyter notebook main.ipynb
```

## Model Overview
The pipeline includes:
- **Feature Extraction**: TF-IDF vectorization
- **Classifier**: Naïve Bayes (BernoulliNB)
- **Evaluation Metrics**: Accuracy, Classification Report

## Evaluation
The model is evaluated based on:
- Accuracy Score
- Precision, Recall, and F1-Score

## License
This project is for educational purposes only.
