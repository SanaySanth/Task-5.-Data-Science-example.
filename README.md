# Kaiburr Assessment 2025 - Task 5: Consumer Complaint Classification

**Author:** SANAY_SANTH  
**Date:** October 20, 2025  
**Task:** 5 - Consumer Complaint Classification  

## Objective
The goal of this project is to build a text classification model that accurately predicts the type of financial complaint based on textual content.  
The model categorizes each complaint into one of the following four classes:

1. Credit Reporting, Repair, or Other  
2. Debt Collection  
3. Consumer Loan  
4. Mortgage  

---

## Steps Implemented

### 1. Explanatory Data Analysis (EDA) and Feature Engineering
- Loaded and inspected 100,000 complaint records from the CFPB dataset.  
- Calculated average text lengths, word counts, and visualized distributions.  
- Analyzed category-wise complaint frequency and top reporting companies.

### 2. Text Preprocessing
- Cleaned complaint narratives by removing punctuation, URLs, and numbers.  
- Used scikit-learn’s `ENGLISH_STOP_WORDS` for simplicity.  
- Tokenized and normalized complaint text for model input.

### 3. Model Selection and Training
- Applied TF-IDF vectorization for text representation.  
- Trained multiple models: Multinomial Naive Bayes, Logistic Regression, and Linear SVC.  
- Compared model performance using accuracy scores.

### 4. Model Evaluation
- Generated classification reports and confusion matrices.  
- The best-performing model achieved high accuracy and balanced class performance.

### 5. Prediction Function
- Implemented a reusable function to classify new complaint text dynamically.  
- Displays predicted category and model confidence score.

### 6. Model Saving & Reporting
- Serialized the best model and TF-IDF vectorizer using `pickle`.  
- Generated a detailed summary report with all required checkpoints.

---

## Results Summary
- **Models trained:** MultinomialNB, LogisticRegression, LinearSVC  
- **Best model:** LinearSVC (highest accuracy and stable training time)  
- **Evaluation metrics:** Accuracy, Precision, Recall, F1-score  
- **Output visualizations:** EDA plots, Word clouds, Model comparison charts, Confusion matrix  
- **All Task 5 specifications fulfilled successfully**


## Conclusion
This project demonstrates a full machine learning pipeline — from data loading and cleaning to training and evaluating text classification models.  
The final model can accurately predict complaint categories and can be extended to real-world deployment scenarios with APIs or dashboards.

✅ Task 5 completed successfully.
