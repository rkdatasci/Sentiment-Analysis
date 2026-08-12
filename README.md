# 🧠 Sentiment Analysis on E-Commerce Product Reviews

An NLP-based sentiment classifier that labels Amazon Alexa customer reviews as **Positive**, **Negative**, or **Neutral** — built to help surface actionable feedback from large volumes of unstructured review text.

## Problem

E-commerce platforms collect thousands of product reviews, but manually reading through them to spot dissatisfaction trends doesn't scale. This project automates sentiment classification so product teams can quickly monitor customer feedback and catch issues early.

## Approach

1. **Data cleaning & preprocessing** — removed noise (HTML tags, punctuation, stopwords), handled missing values, and normalized text casing.
2. **Text preprocessing** — tokenization and vectorization to convert raw review text into model-ready features.
3. **Exploratory data analysis** — examined class balance, review length distribution, and common terms per sentiment class.
4. **Model training** — trained and evaluated multiple classification models (e.g. Logistic Regression, Naive Bayes) using Scikit-learn.
5. **Web app** — built a lightweight web interface for real-time sentiment prediction on new review text.

## Results

- Classified customer reviews into Positive / Negative / Neutral with strong accuracy on the test set.
- Surfaced recurring negative-sentiment keywords useful for product improvement discussions.

## Tech Stack

`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `NLTK` · `Flask/Streamlit` (web app) · `Jupyter Notebook`

## How to Run

```bash
git clone https://github.com/rkdatasci/Sentiment-Analysis.git
cd Sentiment-Analysis
pip install -r requirements.txt
python app.py        # or streamlit run app.py, depending on your setup
```

## What I'd Improve Next

- Fine-tune a transformer-based model (e.g. DistilBERT) for higher accuracy
- Add confidence scores alongside predictions in the web app
- Deploy live (Streamlit Community Cloud / Render) and link the demo here

---
**Author:** Raj Kumar — [LinkedIn](https://www.linkedin.com/in/raj-kumar-0841ba294/) · [GitHub](https://github.com/rkdatasci)
