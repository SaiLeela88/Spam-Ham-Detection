# Spam and Ham Detection using Machine Learning

## 📌 Project Overview

Spam and Ham Detection is a Machine Learning project that focuses on classifying SMS messages into two categories: Spam and Ham.

- **Spam:** Unwanted or fraudulent messages, often containing promotional offers, suspicious links, or misleading information.
- **Ham:** Genuine and legitimate messages exchanged between users.

The project uses Natural Language Processing (NLP) techniques and a supervised Machine Learning algorithm to identify whether an incoming SMS message is spam or legitimate.

## 🎯 Project Objectives

- Analyze SMS messages and identify spam patterns.
- Perform text preprocessing and cleaning.
- Convert text messages into numerical features.
- Build a Machine Learning classification model.
- Classify messages as Spam or Ham.
- Evaluate model performance using accuracy.

## 📊 Dataset Information

The project uses an SMS Spam Collection dataset.

**Dataset size:** 5,572 messages.

| Category | Number of Messages |
|---|---:|
| Ham | 4,825 |
| Spam | 747 |
| Total | 5,572 |

The dataset contains message labels and corresponding SMS text.

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)

## 🔍 Project Workflow

1. Data Loading
2. Data Understanding
3. Data Exploration
4. Label Encoding
5. Train-Test Split
6. Text Cleaning and Preprocessing
7. Feature Extraction using CountVectorizer
8. Model Building using Multinomial Naive Bayes
9. Model Training and Prediction
10. Model Evaluation using Accuracy Score

## 🤖 Machine Learning Algorithm

**Multinomial Naive Bayes**

Multinomial Naive Bayes is a supervised Machine Learning classification algorithm commonly used for text classification problems.

In this project, the algorithm learns patterns from the numerical representation of SMS messages and predicts whether a message belongs to the Spam or Ham category.

## 📝 Text Preprocessing

Text preprocessing is performed to prepare SMS messages for classification.

The project includes:
- Converting text into lowercase.
- Removing special characters and numbers.
- Cleaning unnecessary characters.
- Transforming text into numerical features using CountVectorizer.

## 📈 Model Evaluation

The model's performance is evaluated using Accuracy Score.

Accuracy measures the proportion of correctly classified messages out of the total predictions.

## 🔮 Future Enhancements

- Experiment with TF-IDF feature extraction.
- Compare multiple classification algorithms.
- Evaluate precision, recall, and F1-score.
- Develop an interactive spam detection application.
- Deploy the trained model as a web application.

## 📝 Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be used to identify unwanted SMS messages.

By applying text preprocessing, feature extraction, and Multinomial Naive Bayes classification, the project provides a practical approach to distinguishing spam messages from legitimate communications.

---

**Project Domain:** Machine Learning | NLP | Text Classification

**Algorithm:** Multinomial Naive Bayes

**Language:** Python
