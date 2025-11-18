# 🔍 Consumer Sentiment & Emotion Analysis of Multi-Source(Amazon Reviews + Social Media + News)
📜CodeAlpha Internship — Task 4

# 📖 Overview
This project performs Sentiment Analysis and Emotion Detection on text gathered from:
- Amazon Product Reviews
- Social Media Posts
- News Articles
The objective is to classify text as **Positive, Negative, or Neutral**, analyze emotional patterns, and compare sentiments across multiple platforms.
This project was developed as part of the CodeAlpha Data Analytics Internship (Task-4).

🎯 Objectives :-
- Clean & preprocess raw text data
- Apply VADER and TextBlob rule-based sentiment analysis
- Detect emotional categories using NRC Lexicon
- Train a TF-IDF + Logistic Regression sentiment classifier
- Compare sentiment across 3 different data sources
- Visualize sentiment patterns and save results

🧰 Tech Stack :- 
Programming Language: **Python**
Libraries used :
- Pandas
- NumPy
- NLTK
- VADER Sentiment
- TextBlob
- Scikit-Learn
- Matplotlib
- Seaborn
- WordCloud (optional)

# 🧹 Data Preprocessing Steps
- ✔ Lowercasing
- ✔ Removing URLs, mentions, hashtags
- ✔ Cleaning punctuation & special symbols
- ✔ Removing stopwords
- ✔ Lemmatization
- ✔ Combining multiple datasets into a unified dataframe

# 🧪 Sentiment Analysis Methods
1️⃣ Rule-Based Sentiment:
- VADER Sentiment Analyzer
- TextBlob polarity scoring

2️⃣ Machine Learning Approach:
Convert Amazon star ratings → sentiment labels
- 4–5 ⭐ = Positive
- 3 ⭐ = Neutral
- 1–2 ⭐ = Negative

Train ML model using:
- TF-IDF Vectorizer
- Logistic Regression
- Evaluation metrics used:
- Accuracy
- Precision, Recall, F1-Score

📊 Visualizations Included :-
- Sentiment distribution across sources
- WordCloud for positive words
- WordCloud for negative words
- Confusion matrix (ML model)
- Bar charts & line graphs for trends


👨‍💻 Developed By
-- Ayush
📧 Email: bhanuseenu914@gmail.com
- 🔗 LinkedIn: https://linkedin.com/in/ayush130
- 🔗 GitHub: https://github.com/ayush13-0

📜 License
- This project is licensed under the **MIT License**.
