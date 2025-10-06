# Naive Bayes Projects

This repository contains two machine learning projects using **Naive Bayes classifiers**:

1. **Titanic Survival Prediction** – Gaussian Naive Bayes  
2. **Email Spam Detector** – Multinomial Naive Bayes

---

## 1. Titanic Survival Prediction - Gaussian Naive Bayes

**Objective:** Predict whether a passenger survived the Titanic disaster using features like age, gender, and passenger class.

**Dataset:** `Titanic.csv` (contains all passenger data)

**Methodology:**  
- Cleaned the dataset and handled missing values.  
- Encoded categorical variables and selected important features.  
- Trained a **Gaussian Naive Bayes** classifier.  
- Evaluated model performance using accuracy and other metrics.

**Results:** Accuracy: 78% 

---

## 2. Email Spam Detector - Multinomial Naive Bayes

**Objective:** Classify emails as **spam** or **ham**.

**Dataset:** `spam.csv`

**Methodology:**  
- Preprocessed email text: lowercased, removed punctuation, tokenized.  
- Converted text to numerical features using **CountVectorizer**.  
- Optional: used a **Pipeline** to combine preprocessing and model training.  
- Trained a **Multinomial Naive Bayes** classifier and evaluated performance.

**Results:** Accuracy: 98% 

---

## Folder Structure
Naive-Bayes-Project/
│   README.md
│
├── Titanic_GaussianNB/
│     README.md
│     Project 4-(i).ipynb
│     Titanic.csv
│
└── SpamDetector_MultinomialNB/
      README.md
      Project 4-(ii).ipynb
      spam.csv

