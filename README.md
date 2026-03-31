# 📩 Spam Text Classification using Bag of Words

This project implements a **Spam Detection System** using Natural Language Processing (NLP) techniques and a **Bag of Words (BoW)** model with **Naive Bayes**.

---

## 🚀 Overview

The goal of this project is to classify text messages as **spam** or **ham (not spam)** using machine learning.

Pipeline:
1. Data loading
2. Text preprocessing
3. Feature extraction (Bag of Words)
4. Model training (Naive Bayes)
5. Evaluation
6. Prediction

---

## 📂 Dataset

- Dataset: `spam.csv`
- Contains SMS messages labeled as:
  - `spam`
  - `ham`

---

## ⚙️ Tech Stack

- Python
- Pandas
- NLTK
- Scikit-learn

---

## 🔧 Installation

```bash
pip install pandas nltk scikit-learn
```

Also download NLTK stopwords:

```python
import nltk
nltk.download('stopwords')
```

---

## 🧠 How It Works

### 1. Data Preprocessing
- Convert text to lowercase
- Remove punctuation
- Remove stopwords

### 2. Feature Extraction
- Use **CountVectorizer** (Bag of Words)
- Convert text into numerical vectors

### 3. Model Training
- Algorithm: **Multinomial Naive Bayes**

### 4. Evaluation Metrics
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- Cross-validation score

---

## 📊 Results

- Accuracy: ~97–98%
- Cross-validation accuracy: ~97%
- Strong performance on both spam and ham classes

---

## 🔮 Prediction Example

```python
predict_spam("free money now")        # spam
predict_spam("let's meet tomorrow")  # ham
```

---

## 📁 Project Structure

```
.
├── data/
│   └── spam.csv
├── Text_Classification_using_Bag_of_Words.ipynb
└── README.md
```

---

## 💡 Key Concepts

- Bag of Words (BoW)
- Text preprocessing
- Naive Bayes classification
- Feature vectorization

---

## 🚀 Future Improvements

- Use TF-IDF instead of BoW
- Try advanced models (Logistic Regression, SVM, Deep Learning)
- Deploy as a web app (Flask / FastAPI)
- Add real-time prediction API

---

## 👨‍💻 Author

**Devendra Kushwah**
