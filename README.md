# Human vs LLM Generated Text Detection

## Overview
This project implements a baseline machine learning pipeline to distinguish human-written text from LLM-generated content using TF-IDF features and linear classifiers.

## Methodology
- Dataset: Balanced dataset (Human + LLM samples)
- Preprocessing: Lowercasing and basic cleaning
- Feature Engineering: TF-IDF (Unigram + Bigram)
- Models:
  - Logistic Regression
  - Linear SVM

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Future Improvements
- Cross-domain evaluation
- Robustness testing
- Transformer-based models
