🧠 Claim or Not: Classifying User Comments Using Logistic Regression
This project applies Natural Language Processing (NLP) and Logistic Regression to classify user comments as either claims (factual, verifiable statements) or non-claims (opinions or irrelevant content). It helps in building intelligent systems for fact-checking, moderation, and content filtering.

📝 Objective
Input: A user-generated comment or statement.

Output: Binary classification — Claim (factual) or Not a Claim (opinion/other).

🚀 Key Features
🧹 Text Preprocessing:

Lowercasing, punctuation removal

Tokenization, stopword removal

Lemmatization (optional depending on pipeline)

🔤 Vectorization:

TF-IDF (Term Frequency–Inverse Document Frequency) for transforming text into feature vectors.

🤖 Model:

Logistic Regression classifier for binary text classification.

📈 Evaluation:

Accuracy, Precision, Recall, F1-Score, Confusion Matrix.

🛠️ Tech Stack
Python

Scikit-learn

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook

📁 Files
claim_or_not.ipynb: Main notebook containing all steps — data preprocessing, TF-IDF vectorization, Logistic Regression training, and evaluation.

📌 Sample
Input:
"The Earth revolves around the Sun."
Output: Claim

Input:
"I think that movie was amazing!"
Output: Not a Claim
