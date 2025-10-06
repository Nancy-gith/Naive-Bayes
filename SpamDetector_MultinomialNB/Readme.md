# Email Spam Detector - Multinomial Naive Bayes

## Objective
This project aims to classify **emails** as **spam** or **ham (not spam)** using the **Multinomial Naive Bayes** algorithm. It is a widely used text classification task in email filtering systems to automatically detect unwanted messages.

## Dataset
- **File:** `spam.csv`  
- **Features:** Each email has a `category` (spam or ham) and the `message` content of the email.

## Steps and Methodology
1. **Data Exploration:** 
   - Checked for missing values and analyzed the distribution of spam vs. ham emails.
   - Observed common patterns and frequent words in spam emails.

2. **Text Preprocessing:** 
   - Tokenized the email content into individual words to prepare for feature extraction.

3. **Feature Extraction:** 
   - Applied **CountVectorizer** to convert emails into numerical features. This method counts the frequency of each word, helping the model learn which words are strong indicators of spam.
   - Also used an **alternative approach with a Pipeline**, combining vectorization and model training in one step. This made the workflow simpler and ensured preprocessing and model fitting happened sequentially.

4. **Model Training and Evaluation:** 
   - Trained a **Multinomial Naive Bayes** classifier on the processed data.
   - Keywords like “free”, “win”, “urgent”, and “offer” were strong indicators of spam emails.

## Results
- **Accuracy:** 98% 
- **Observations:** The model successfully distinguished spam from ham emails, performing very well on this dataset.

## How to Run
1. Open `Project 4-(ii).ipynb` in Jupyter Notebook.
2. Make sure `spam.csv` is in the same folder.
3. Run all cells to preprocess the data, train the model, and evaluate performance.

## Files
- `Project 4-(ii).ipynb` → Jupyter Notebook with complete workflow  
- `spam.csv` → Dataset  
- `README.md` → Project description
