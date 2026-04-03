# Fake News Detection with Confidence Analysis

## Overview
In this project, I built a machine learning model to classify news articles as real or fake. The main idea was not just to make predictions, but also to understand how confident the model is in its decisions.

---

## What I Did
- Loaded and cleaned the dataset  
- Converted text data into numerical features using TF-IDF  
- Trained a Logistic Regression model  
- Evaluated model performance using accuracy  
- Analyzed prediction confidence to understand reliability  

---

## Results
- The model achieved good overall accuracy  
- However, confidence scores varied across predictions  

---

## Key Observation
While many predictions were made with high confidence, there were several cases where the model showed low confidence (below 0.6).

These low-confidence predictions indicate situations where the model is uncertain and may not be reliable.

---

## What I Learned
- High accuracy does not always mean reliable predictions  
- Confidence scores can help identify uncertain outputs  
- It is important to analyze model behavior, not just performance  

---

## Tools Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- TF-IDF Vectorizer  

---

## Conclusion
This project helped me understand that machine learning models should not only be evaluated based on accuracy, but also on how confident and consistent their predictions are. This is important when building systems that need to be trustworthy.

---

## Author
Krishal Sukdeve
