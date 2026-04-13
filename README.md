# 🎬 Movie Review Sentiment Analysis

Predict whether a movie review is positive or negative using NLP and Machine Learning.

## Problem
Businesses need to understand customer sentiment from text reviews automatically.

## Dataset
- Source: IMDB Dataset of 50K Movie Reviews (Kaggle)
- 50,000 reviews | Balanced: 25K positive, 25K negative

## Results
| Metric | Value |
|--------|-------|
| Accuracy | 89.55% |
| Precision | 0.90 |
| Recall | 0.90 |
| F1-Score | 0.90 |

## How It Works
1. Clean text (remove HTML, special characters)
2. Convert text to numbers using TF-IDF
3. Classify using Logistic Regression

## Interactive Demo
Built with Gradio - paste any review and get instant sentiment prediction

## Tools
Python | Pandas | Scikit-learn | NLTK | Matplotlib | Gradio
