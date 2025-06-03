# 📊 Social Media Sentiment Analysis

A Streamlit web app that performs sentiment analysis on tweets using a machine learning model. This project allows users to either input custom tweets or fetch live tweets from a public Twitter account using the `ntscraper` (Nitter) module, and displays whether the sentiment is **positive** or **negative**.

## 🚀 Features

- 🔍 Sentiment prediction on user-inputted tweets or scraped tweets from Twitter usernames.
- 🐦 Live tweet scraping using the `ntscraper` package (no Twitter API key needed).
- 🧠 Machine Learning model trained on tweet data using TF-IDF vectorization.
- 🧹 Text preprocessing: cleaning, lowercasing, tokenization, and stopword removal.
- 🎨 Stylish and interactive Streamlit UI with colored sentiment cards.
- ⚡ Fast loading and optimized resource usage with Streamlit caching.

## 🛠️ Tech Stack

- Python 3.x
- Streamlit
- scikit-learn
- nltk
- ntscraper

## 📂 Project Structure

```
.
├── app.py                          # Streamlit application for sentiment analysis
├── Twitter_sentiment_Analysis.ipynb  # Jupyter notebook for training and analysis
├── model.pkl                       # Trained ML model (e.g., SVM or Logistic Regression)
├── vectorizer.pkl                  # Trained TF-IDF vectorizer
├── requirements.txt                # Required Python packages
└── README.md                       # Project documentation
```

## 💡 How It Works

1. User selects either "Input tweet" or "Get tweets from user".
2. The text is cleaned and tokenized using regex and NLTK stopwords.
3. TF-IDF vectorization converts the text into a numerical format.
4. A pre-trained ML model predicts the sentiment as **Positive** or **Negative**.
5. Results are displayed using Streamlit with color-coded cards (green for positive, red for negative).

## 📥 Dataset Used

https://www.kaggle.com/datasets/kazanova/sentiment140

## 🖼️ Screenshot

![Output_Screenshot](https://github.com/user-attachments/assets/123dbeca-a51c-44a7-bc49-6c51d6b31442)


## 📦 requirements.txt

```
streamlit
scikit-learn
nltk
ntscraper
```

## 👨‍💻 Author

**Barun Paul** — Developer and ML Enthusiast
