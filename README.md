# 📧 SPAM-HAM Classification Using Bag of Words (BoW)

This project implements a binary text classification model to detect **spam** or **ham (non-spam)** SMS messages. It uses the **Bag of Words** approach for feature extraction, along with machine learning classification algorithms. Text preprocessing is done using **spaCy**.

---

## 🛠️ Tech Stack

- **Python**
- **pandas**
- **scikit-learn**
- **spaCy**
- **CountVectorizer** (BoW)
- **Multinomial Naive Bayes** (ML Model)

---

## 🧹 Preprocessing Steps (spaCy)
- Lowercasing
- Tokenization
- Lemmatization
- Stopword removal
- Filtering non-alphabetic tokens

---

## 📊 Model Performance

### ✅ Accuracy:
`0.9596` (≈ 96%)

### 🧾 Classification Report:
| Label | Precision | Recall | F1-score | Support |
|-------|-----------|--------|----------|---------|
| Ham (0) | 0.99 | 0.96 | 0.98 | 966 |
| Spam (1) | 0.80 | 0.94 | 0.86 | 149 |

**Overall Metrics:**
- **Accuracy**: 0.96
- **Macro Avg F1-score**: 0.92
- **Weighted Avg F1-score**: 0.96

---

## 📂 How to Run

1. Install dependencies:
   ```bash
   pip install pandas scikit-learn spacy
   python -m spacy download en_core_web_sm
2. Run the cells step by step

3. Observe the preprocessing, model training, and evaluation results

📁 Dataset
Dataset used: SMS Spam Collection Dataset

🧠 Future Improvements
Use TfidfVectorizer for better text representation.

Try other models like Logistic Regression, SVM, or ensemble methods.

Integrate with a frontend (e.g., Streamlit) for live SMS classification.
