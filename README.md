# Phishing Email Detection

## Abstract
This project aims to develop a machine learning model to detect phishing emails using Natural Language Processing (NLP) techniques. By preprocessing email text and extracting features using TF-IDF, the model classifies emails as either phishing or legitimate. Multiple classification algorithms are implemented to evaluate their effectiveness, with a focus on the accuracy of predictions.

## Keywords
Phishing detection, email classification, machine learning, Natural Language Processing (NLP), TF-IDF, Logistic Regression, Random Forest.

## Introduction
Phishing attacks have become increasingly prevalent, posing significant risks to individuals and organizations alike. This project addresses the challenge of identifying phishing emails by employing machine learning techniques to analyze and classify email content. The use of NLP enables effective preprocessing and feature extraction, which are crucial for building robust predictive models.

## Methodology
1. **Data Collection**: A dataset of phishing emails is loaded, containing features such as email text and labels indicating whether they are phishing or legitimate.
2. **Data Preprocessing**:
   - Special characters and numbers are removed from email texts.
   - Text is converted to lowercase and stopwords are eliminated to enhance feature quality.
3. **Feature Extraction**: The TF-IDF Vectorizer is used to transform cleaned email texts into a numerical format suitable for machine learning algorithms.
4. **Model Selection**: Logistic Regression and Random Forest classifiers are chosen for training and evaluation.

## Implementation Details
### Requirements
To run this project, you need to install the following libraries:

```bash
pip install pandas scikit-learn nltk matplotlib seaborn tensorflow keras
