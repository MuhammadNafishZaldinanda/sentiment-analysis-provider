# Sentiment Analysis of Cellular Service Provider Tweets

This project aims to analyze public sentiment toward cellular service providers through Twitter posts. We apply traditional NLP techniques and train a Support Vector Machine (SVM) model to classify tweets into **positive** or **negative** sentiments.

---

## How to Run Notebook
Install all dependency / python modules. Better using virtualenv and separate the environment between one and other services.

```
(sentiment) $ pip install -r requirements.txt
```

Then, open and run:

```
sentiment-analysis-providers.ipynb
```


Inside this notebook:

- Data understanding dataset text tweet
- Preprocessing dataset text tweet
- Transform text using TF-IDF vectorizer
- Train a sentiment classification model using SVM
- Perform hyperparameter tuning using RandomizedSearchCV
- Evaluate model performance using classification metrics and confusion matrix
- Save the final model and vectorizer using joblib

## Output Files

```
TF-ID.joblib (vectorizer)
svm-sentiment-model-default.joblib (default parameter)
svm-sentiment-model-optimized.joblib (optimized paramter)
```

## Inferece
open and run:
```
inference.ipynb
```


