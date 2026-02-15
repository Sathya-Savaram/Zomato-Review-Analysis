# 🍽️ Zomato Review Sentiment Analysis – NLP Project

---

## 📌 Project Overview

This project performs **Sentiment Analysis** on restaurant reviews from Zomato using **Python and Natural Language Processing (NLP)** techniques.

The objective is to analyze customer feedback and classify reviews as **Positive** or **Negative**, enabling businesses to understand customer satisfaction patterns.

---

## 🎯 Business Objective

- Understand customer sentiment from textual reviews  
- Identify positive and negative feedback patterns  
- Apply NLP techniques for text cleaning and feature engineering  
- Build and evaluate a Machine Learning classification model  

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **NLTK**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 📂 Dataset Information

**File:** `Restaurant_Reviews.tsv`

The dataset contains:

- Review text
- Sentiment label (0 = Negative, 1 = Positive)

---

## 🔎 Data Preprocessing & NLP Steps

The following preprocessing techniques were applied:

- Text lowercasing  
- Removing punctuation & special characters  
- Stopword removal  
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

### Evaluation Metrics:
- Accuracy Score
- Confusion Matrix

The model successfully classified customer sentiments with strong predictive performance.

---

## 📊 Key Insights

- Majority of customer reviews are positive.
- Proper text preprocessing significantly improves model performance.
- Naive Bayes performs effectively for binary text classification problems.
- NLP enables extraction of structured insights from unstructured text data.

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

### Step 1: Clone the Repository

```
git clone https://github.com/Sathya-Savaram/Zomato-Review-Analysis.git
```

### Step 2: Navigate to Project Folder

```
cd Zomato-Review-Analysis
```

### Step 3: Install Required Libraries

```
pip install pandas numpy nltk scikit-learn
```

### Step 4: Download NLTK Stopwords (First Time Only)

Open Python and run:

```python
import nltk
nltk.download('stopwords')
```

### Step 5: Open Jupyter Notebook

```
jupyter notebook
```

Then open:

```
Zomato_Reviews_Analysis.ipynb
```

Run all cells to execute the full workflow.

---

## 📌 Conclusion

This project demonstrates:

- End-to-end NLP workflow  
- Text preprocessing and feature engineering  
- Supervised Machine Learning classification  
- Model evaluation using standard metrics  

It showcases practical application of Natural Language Processing for business sentiment analysis.

---
