# 📰 NaivePress – A News Classifier Using Naive Bayes

`NaivePress` is a simple but powerful news headline classifier built from scratch using Python. It uses a Naive Bayes algorithm to determine whether a headline is related to **Politics**, **Finance**, or any other added category.

---

## 🚀 Features

- Pure Python implementation (no ML libraries)
- Tokenization using NLTK
- Laplace smoothing for unseen words
- Custom probability-based predictions
- Confidence visualizations with matplotlib
- Easy to extend with more categories

---

## 📊 How It Works

1. Tokenizes text using `nltk.word_tokenize`
2. Calculates word frequency per category
3. Converts frequencies to probabilities with Laplace smoothing
4. During prediction, multiplies category priors with word likelihoods
5. Returns the category with the highest probability
6. Optionally visualizes prediction confidence

---

## 📦 Dependencies

```bash
pip install nltk  matplotlib pandas

