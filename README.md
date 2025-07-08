# Sentimental-Analysis-Using-Naive-Bayes-Classifier
# 🎬 IMDB Sentiment Analysis (50K Movie Reviews)

🔍 Perform sentiment classification on 50,000 IMDB movie reviews using traditional Machine Learning or Deep Learning models (e.g., Naive Bayes, LSTM, BERT).

---

## 📚 Dataset

- Total: **50,000 movie reviews**
  - 25,000 for training
  - 25,000 for testing
- Labels: `positive` / `negative` (binary)
- Format: `.csv`
- Sources:
  - 📥 [Kaggle Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
  - 🌐 [Stanford AI Lab](http://ai.stanford.edu/~amaas/data/sentiment/)

---

## 🎯 Objective

- Build models to classify the sentiment of movie reviews:
  - ✅ Traditional ML: Naive Bayes, Logistic Regression, SVM
  - ✅ Deep Learning: LSTM, BiLSTM, BERT

---

## 🧠 Project Pipeline

1. **Load dataset**
2. **Text preprocessing**
   - Lowercasing
   - Removing punctuation and stopwords
   - Tokenization
3. **Feature extraction**
   - CountVectorizer / TF-IDF / Embeddings
4. **Model training**
5. **Model evaluation**

---

## 📈 Evaluation Metrics

- Accuracy
- Precision / Recall
- F1-score
- Confusion Matrix
- ROC-AUC (optional)

---

## 🧪 Example Output

```text
"This movie was amazing! The plot and characters were unforgettable."
→ Predicted: Positive
