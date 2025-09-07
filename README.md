# Task 1 — AG News Text Classification (Internship Project)

## 📌 Objective
The goal of this task was to build a **news headline topic classifier** that can predict the category of a given news headline.  
We used the **AG News dataset** which contains 4 categories:
- World
- Sports
- Business
- Sci/Tech

---

## 🛠️ Approach
For simplicity and efficiency, we implemented a **classical machine learning model** instead of fine-tuning a large Transformer.  
Steps followed:
1. Loaded the AG News dataset from Hugging Face `datasets`.
2. Preprocessed text using **TF-IDF vectorization** (top 5000 features).
3. Trained a **Logistic Regression** classifier.
4. Evaluated the model using **Accuracy, Precision, Recall, F1-score**.
5. Tested on custom news headlines.

---

## 📊 Results
- **Accuracy:** XX%  
- **Weighted F1 Score:** XX%  

(Replace XX with your results from `classification_report`)

---

## 💻 Example Predictions
```python
Input: "Microsoft announces new AI breakthrough"
Output: Sci/Tech

Input: "Pakistan wins T20 cricket match"
Output: Sports
## 📊 Results
- **Accuracy:** 91%
- **Weighted F1 Score:** 91%
