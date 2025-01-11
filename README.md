## 📊 Day 6: Sentiment Analysis with NLP – IMDB Top 1000 Dataset

### 📄 Project Overview
This project focuses on performing **Sentiment Analysis** on movie overviews from the **IMDB Top 1000 Dataset** using **Natural Language Processing (NLP)** techniques. The goal is to classify sentiments as **Positive**, **Neutral**, or **Negative** based on IMDB ratings.

**Dataset Link:** [IMDB Top 1000 Dataset](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows)

---

### 🎯 Objective
- Preprocess movie overviews and extract meaningful numerical features using NLP techniques.
- Build a Logistic Regression model to classify sentiment based on textual data.
- Evaluate model performance and visualize key results.

---

### 📊 Dataset Description
- **Overview:** A brief description of the movie or TV show.
- **IMDB_Rating:** The IMDB rating for the movie/TV show (used to classify sentiment).
- **Features Used:** Cleaned `Overview` column and TF-IDF vectorized features.

**Target Variable: Sentiment**
- **Positive:** Ratings > 8.0
- **Neutral:** Ratings between 7.0 and 8.0
- **Negative:** Ratings < 7.0 (if present).

---

### 🛠️ Steps Performed

#### 1. Data Preprocessing
- Cleaned the `Overview` column by removing punctuation, numbers, and converting text to lowercase.
- Handled missing values by dropping rows with missing overviews.

#### 2. Feature Engineering
- Used **TF-IDF Vectorizer** to convert text into numerical features.
- Limited the number of features to 5000 for efficiency.

#### 3. Model Training
- Trained a **Logistic Regression** model to classify sentiments.

#### 4. Model Evaluation
- Evaluated performance using:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix

#### 5. Insights
- Identified the top 20 words strongly associated with positive sentiment.

---

### 📊 Results
- **Accuracy:** Achieved a high accuracy score for sentiment classification.
- **Key Words for Positive Sentiment:** Words like `masterpiece`, `amazing`, `brilliant` were identified as most impactful.

