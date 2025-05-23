# 📚 Sentiment Analysis on IMDB Movie Reviews

This project performs binary sentiment classification on IMDB movie reviews using various machine learning algorithms. The goal is to predict whether a given movie review is **positive** or **negative**.

---

## 📂 Dataset

- **Source**: [Kaggle - IMDB Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Total Reviews**: 50,000  
  - 25,000 Positive  
  - 25,000 Negative

---

## 🛠️ Preprocessing

- Removal of HTML tags, punctuation, and stopwords
- Conversion to lowercase
- Tokenization using NLTK
- Stemming with Porter Stemmer
- Removal of 418 duplicate reviews
- Text vectorization using **TF-IDF**

---

## 🤖 Machine Learning Models Used

| Model                        | Accuracy   |
|-----------------------------|------------|
| Logistic Regression         | **89.25%** |
| Support Vector Machine      | **89.88%** |
| Multinomial Naive Bayes     | 86.06%     |
| K-Nearest Neighbors (KNN)   | 74.88%     |
| Decision Tree Classifier    | 70.36%     |

- Best performer: **Support Vector Machine (SVM)**
- Fastest training: **Multinomial Naive Bayes**
- Worst performer: **Decision Tree**

---

## 📊 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Precision, Recall, and F1-score

---

## 📈 Visualizations

- Class distribution plots (countplot, pie chart)
- Model comparison bar chart
- Word clouds for positive and negative reviews

---

## 📦 Libraries Used

- `pandas`, `numpy`
- `nltk`
- `sklearn`
- `matplotlib`, `seaborn`

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-imdb.git
   cd sentiment-analysis-imdb
