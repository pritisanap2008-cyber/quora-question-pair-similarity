# Quora Question Pair Similarity

Predicts whether two Quora questions mean the same thing (duplicate or not).

- Data: Quora Question Pairs (GLUE), 50,000 random pairs
- Text cleaning, 11 features (word counts, common words, fuzzy match scores, TF-IDF similarity)
- Models: Logistic Regression and XGBoost
- Best result: XGBoost + TF-IDF, log loss 0.4886, accuracy 72.57%
- Tools: Python, pandas, scikit-learn, rapidfuzz, XGBoost, Google Colab
