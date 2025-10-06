# Titanic Survival Prediction - Gaussian Naive Bayes

## Objective
The goal of this project is to predict whether a passenger survived the Titanic disaster using the passenger's features. This is a classic binary classification problem where we apply the **Gaussian Naive Bayes** algorithm.

## Dataset
- **Source:** Titanic dataset (Kaggle)
- **Features include:** Passenger class, sex, age, number of siblings/spouses aboard, number of parents/children aboard, fare, cabin, and port of embarkation.

## Steps and Methodology
1. **Data Exploration:** Understand dataset, check for missing values, visualize distributions.
2. **Data Cleaning:**
   - Fill missing values (e.g., age, cabin)
   - Encode categorical variables (e.g., Sex)
3. **Feature Selection:** Select relevant features for model training.
4. **Data Splitting:** Split dataset into training and testing sets.
5. **Model Training:** Train a Gaussian Naive Bayes classifier on the training set.
6. **Prediction & Evaluation:** Predict on test data and calculate accuracy, precision, recall, and F1-score.

## Model Used
- **Gaussian Naive Bayes:** Assumes continuous features follow a normal (Gaussian) distribution.  
- Suitable for numeric data and small datasets.

## Results
- **Accuracy:** 78% 
- **Observations:** Gender and passenger class were the most important features in predicting survival.

## How to Run
1. Open `Project 4-(i).ipynb` in Jupyter Notebook.
2. Make sure `Titanic.csv` is in the same folder.
3. Run all cells to preprocess, train, and evaluate the model.

## Files
- `Project 4-(i).ipynb` → Jupyter Notebook with code and analysis  
- `Titanic.csv` → Dataset files  
- `README.md` → Project description
