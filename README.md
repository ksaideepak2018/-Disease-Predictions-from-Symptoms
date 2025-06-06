# -Disease-Predictions-from-Symptoms

This project aims to enable early and accurate disease detection by analyzing user-reported symptoms using machine learning techniques. It focuses on predicting conditions such as diabetes and heart disease using a structured, data-driven approach.

## Project Overview

Using a combination of text preprocessing, vectorization, and supervised learning models, this system predicts diseases based on user input. It integrates web scraping, symptom similarity analysis, and multiple models to maximize diagnostic accuracy while remaining user-friendly and interactive.

## Features

- Symptom preprocessing and expansion using NLP techniques
- Cosine similarity and TF-IDF-based ranking of probable diseases
- Integration of real-time disease information from Wikipedia
- Multiple ML models: Logistic Regression, Random Forest, Decision Tree, Naive Bayes
- 5-fold cross-validation for performance evaluation
- Interactive interface for symptom entry and prediction feedback

## Technologies Used

- Python
- Scikit-learn (Logistic Regression, Naive Bayes, Random Forest, Decision Tree)
- TF-IDF Vectorization
- Cosine Similarity
- Web scraping with `requests` and `BeautifulSoup`
- NLTK for lemmatization and stopword removal
- Jaccard similarity for symptom comparison

## Methodology

1. **Data Acquisition & Cleaning**: Data was gathered from trusted health portals and structured into disease-symptom pairs.
2. **Symptom Preprocessing**: Tokenization, lemmatization, stopword removal, synonym mapping.
3. **Vectorization**: User input and disease profiles converted to binary or TF-IDF vectors.
4. **Model Training**: Trained models using labeled vectors with supervised learning techniques.
5. **Prediction & Output**: Diseases ranked by similarity score and predictive confidence.
6. **Evaluation**: Models validated via cross-validation and evaluated using accuracy and recall metrics.

## Results

| Model                     | Accuracy | Recall | Cross-Validation Accuracy |
|--------------------------|----------|--------|----------------------------|
| Logistic Regression       | 91.74%   | 91.74% | 89.19%                     |
| Random Forest             | 92.31%   | 92.31% | 86.92%                     |
| Decision Tree             | 91.97%   | 91.97% | 83.62%                     |
| Multinomial Naive Bayes   | 85.29%   | 85.29% | 84.50%                     |


---

