# 🌐 Language Detection using Naive Bayes and TF-IDF

This project is a simple yet powerful **Natural Language Processing (NLP)** model to identify the language of a given text using:
- Text preprocessing
- TF-IDF feature extraction
- Naive Bayes classifier

It supports multiple languages and demonstrates strong performance across various scripts and language families.

---

## 🧠 Features

- Detects language from text inputs
- Supports multiple languages including:
  - English
  - Arabic
  - Hindi
  - Tamil
  - And more!
- Visualizes performance using a confusion matrix
- Lightweight and efficient

---

## 🚀 Technologies Used

- Python 3
- scikit-learn
- pandas, seaborn, matplotlib
- nltk (for stopword removal and stemming)
- Naive Bayes (Multinomial)
- TF-IDF Vectorizer

---

## 📂 Dataset

The dataset used for training is `text_language.csv`, which contains labeled sentences in different languages.

---

## 🔧 How It Works

1. The data is cleaned and normalized using regex and lowercasing.
2. Features are extracted using **TF-IDF Vectorizer**.
3. A **Multinomial Naive Bayes** model is trained.
4. The model is evaluated using **accuracy** and **confusion matrix**.
5. A helper function `lang_predict()` lets you input any sentence and returns the predicted language.

---

## 🧪 Sample Results

```python
lang_predict("Today is going to be very busy...")
# Output: English

lang_predict("आज का दिन बहुत व्यस्त रहने वाला है...")
# Output: Hindi

lang_predict("سيكون اليوم مشغولاً للغاية...")
# Output: Arabic
```

## 📈 Accuracy

Achieved an accuracy of over 97% on test data.
The model demonstrates high reliability in identifying multiple languages across different scripts.

Confusion matrix and classification report included for detailed performance analysis.

## 🖼️ Visualizations

🔹 Confusion Matrix

<img src="assets/Confusion_matrix.png" alt="Confusion Matrix" width="600"/>

## 📥 Installation & Running

🔧 Clone the Repository

git clone https://github.com/Noel-Lawrence-2004/Language-Detector.git

## 📦 Install Dependencies

pip install -r requirements.txt

## ▶️ Run the Script

python Language_detector.ipynb
