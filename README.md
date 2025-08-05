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




🔥 Viral Video/Post Reach Prediction
This project predicts whether a YouTube video (from the DEvideos dataset) will have high reach (viral) or low reach based on features like likes, dislikes, comment count, etc.

📌 Project Overview
✅ Objective: Predict the virality of a video based on user interactions (likes, dislikes, comment count)

📊 Dataset: DEvideos.csv (from the YouTube Trending Video Dataset)

🤖 Models Used:

Logistic Regression

Random Forest Classifier

📈 Evaluation: Confusion Matrix with Heatmap, Accuracy, Precision, Recall, F1 Score

⚙️ Features Used
likes

dislikes

comment_count

views (used to define virality threshold)

🧠 Target Variable
is_viral: Binary label derived from whether views are greater than the 75th percentile (1 = Viral, 0 = Not Viral)

🏗️ How It Works
Preprocess the dataset

Remove missing values

Select relevant columns

Create is_viral label

Train-Test Split

80% training, 20% testing

Model Training

Logistic Regression or Random Forest is trained on features

Prediction & Evaluation

Predict is_viral on test data

Evaluate using confusion matrix & classification report

Visualize performance with a Seaborn heatmap


               Predicted
            |  Not Viral |  Viral
True -------|------------|--------
 Not Viral  |     55     |   12
 Viral      |     9      |   64


👨‍💻 Author
Chittypolu Deepak


