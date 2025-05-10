# 🧠 Toxic Comment Classification using Logistic Regression

This project aims to classify social media comments as toxic or non-toxic using machine learning. It serves as an early step toward identifying signs of depression or harmful content in online conversations.

## 🔍 Project Overview

- Goal: Classify toxic comments using traditional machine learning models
- Dataset: Jigsaw Toxic Comment Classification Challenge (from Kaggle)
- Model Used: Logistic Regression
- Feature Extraction: TF-IDF Vectorization

## 🗂️ Dataset

The dataset contains user comments labeled with different types of toxicity:

- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate

For this project, we simplified the task to binary classification:  
📌 Toxic vs Non-Toxic

## 🧪 Approach

1. Data Preprocessing:
   - Lowercasing
   - Removing punctuation, numbers, and stop words
   - Tokenization

2. Feature Engineering:
   - TF-IDF vectorization of cleaned text

3. Model Training:
   - Logistic Regression using scikit-learn

4. Evaluation:
   - Accuracy, Precision, Recall, F1 Score
   - Confusion Matrix
   - ROC Curve

## 📈 Results

- Achieved good performance in detecting toxic vs non-toxic comments.
- The model is lightweight and interpretable.
- Can be further improved with ensemble models or deep learning.

## 🛠 Tools & Technologies

- Python
- Google Colab
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- nltk for text preprocessing

## 📌 Future Enhancements

- Use deep learning models like LSTM or BERT
- Integrate with social media APIs for real-time comment screening
- Build a web dashboard for live classification

## 📁 Files in this Repo

- Toxic_Comment_Classification.ipynb — Colab notebook with full workflow
- README.md — You're reading it!
- (Optional) requirements.txt — List of required packages (if using a virtual environment)

## 🤝 Acknowledgements

- [Kaggle Jigsaw Toxic Comment Dataset](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)
- Inspired by the mission to build a safer online community

---

Made by Mushraf Taranum and Anisa Unisa
