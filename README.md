# 🍽️ Zomato Review Sentiment Analysis – NLP Project

---

## 📌 Project Overview

This project performs **Sentiment Analysis** on Zomato restaurant reviews using **Python and Natural Language Processing (NLP)** techniques.

The objective is to classify customer reviews as **Positive (1)** or **Negative (0)** to understand customer satisfaction patterns.

---

## 🎯 Business Objective

- Analyze customer sentiment from textual reviews  
- Identify positive and negative feedback patterns  
- Apply NLP techniques for text preprocessing  
- Build and evaluate a machine learning classification model  

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- NLTK  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Dataset Information

**File:** `Restaurant_Reviews.tsv`

The dataset contains:

- Review text  
- Sentiment label (0 = Negative, 1 = Positive)

---

## 🔎 Data Preprocessing & NLP Steps

The following NLP techniques were applied:

- Text lowercasing  
- Removal of punctuation & special characters  
- Stopword removal using NLTK  
- Stemming using PorterStemmer  
- Tokenization  
- Feature extraction using **Bag of Words (CountVectorizer)**  

---

## 🤖 Machine Learning Model

### Algorithm Used:
- **Naive Bayes Classifier**

### Workflow:
1. Train-Test Split  
2. Model Training  
3. Prediction on test data  
4. Model Evaluation  

### 📊 Model Performance

- Accuracy Score: **71%**
- Confusion Matrix Used for Evaluation  

The Naive Bayes classifier achieved 71% accuracy on the test dataset, demonstrating effective performance for binary text classification.

---

## 📁 Project Structure

```
Zomato-Review-Analysis/
│
├── Restaurant_Reviews.tsv
├── Zomato_Reviews_Analysis.ipynb
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/Sathya-Savaram/Zomato-Review-Analysis.git
```

### 2️⃣ Navigate to Project Folder

```
cd Zomato-Review-Analysis
```

### 3️⃣ Install Required Libraries

```
pip install pandas numpy nltk scikit-learn
```

### 4️⃣ Download NLTK Stopwords (First Time Only)

Open Python and run:

```python
import nltk
nltk.download('stopwords')
```

### 5️⃣ Open Jupyter Notebook

```
jupyter notebook
```

Open:

```
Zomato_Reviews_Analysis.ipynb
```

Run all cells to execute the full workflow.

---

## 📌 Key Learnings

- End-to-end NLP pipeline implementation  
- Text preprocessing and feature engineering  
- Supervised Machine Learning for classification  
- Model evaluation using Accuracy Score & Confusion Matrix  

---

## 📌 Conclusion

This project demonstrates practical application of **Natural Language Processing and Machine Learning** to extract insights from unstructured text data and perform sentiment classification effectively.

---
