# Flipkart Customer Reviews Sentiment Analysis

Analyze Flipkart product reviews using **Text Mining**, **NLP**, and **Logistic Regression** to identify positive and negative customer feedback for product improvement.

---

## 📌 Project Objectives

- Clean and preprocess raw review text
- Apply text mining and NLP techniques
- Train a logistic regression model to classify sentiment
- Identify top words that influence customer sentiment
- Provide insights to support product development

---

## 🛠️ Tools & Techniques

- **Text Mining**: stopword removal, regex cleaning
- **NLP**: TF-IDF vectorization
- **Modeling**: Logistic Regression
- **Evaluation**: Confusion matrix, classification report
- **Visualization**: Top sentiment-driving keywords

---

## 🧠 Workflow Overview

1. **Load & inspect** raw review data  
2. **Preprocess** text (cleaning + stopwords removal)  
3. **Convert** ratings to sentiment (positive / negative)  
4. **Balance** the dataset to avoid bias  
5. **Vectorize** text using TF-IDF  
6. **Train** logistic regression classifier  
7. **Evaluate** using precision, recall, F1-score  
8. **Visualize** top positive and negative words  

---

## ⚙️ How to Run

1. Open the notebook:  
   ```
   flipkart_sentiment_summary.ipynb
   ```

2. Make sure the dataset is in the same directory:  
   ```
   flipkart_reviews_raw.csv
   ```

3. Run all cells step-by-step.

---

## 📊 Example Output

- Confusion Matrix:
  ```
  [[ TN, FP ],
   [ FN, TP ]]
  ```

- Classification Report:
  - Precision, Recall, F1-score

- Top Words Plot:
  Shows which words push reviews positive or negative.

---

