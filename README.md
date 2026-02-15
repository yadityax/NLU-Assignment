# Sports vs Politics Text Classification

Binary text classification system to distinguish between Sports and Politics news articles using machine learning.

## Dataset
- **Source**: Kaggle News Category Dataset (rmisra/news-category-dataset)
- **Samples**: 2,000 balanced articles (1,000 Sports + 1,000 Politics)
- **Format**: Short text (headlines + descriptions) from HuffPost (2012-2022)

## Features
- Bag of Words (BoW) with bigrams
- TF-IDF with bigrams and trigrams
- Maximum 5,000 features

## Models Tested
1. Multinomial Naive Bayes
2. Logistic Regression
3. Linear SVC (Best: 95.51% test accuracy)
4. Random Forest
5. Logistic Regression with trigrams

## Data Split
- Training: 70% (1,400 samples)
- Validation: 10% (199 samples)
- Test: 20% (401 samples)

## Best Results
**LinearSVC with TF-IDF (1-2 grams)**
- Test Accuracy: 95.51%
- Validation Accuracy: 92.46%
- Precision: 0.955 | Recall: 0.955 | F1: 0.955

