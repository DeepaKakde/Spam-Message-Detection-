# 📩 Spam Message Detection

A Machine Learning project that classifies SMS messages as **Spam** or **Ham** using Natural Language Processing.

## 🎯 Project Goal

The main goal of this project is to automatically identify unwanted or promotional messages and separate them from normal messages.

## 🔍 How It Works

The project follows a simple pipeline:

**SMS Message → Text Cleaning → TF-IDF → Machine Learning Model → Prediction**

### Text Processing
- Convert text to lowercase
- Remove special characters
- Tokenization
- Remove English stopwords

### Feature Extraction
Used **TF-IDF Vectorizer** with a maximum of 2000 features.

### Models Tested

| Model | Accuracy | F1 Score |
|---|---:|---:|
| Gaussian Naive Bayes | 80.85% | 51.71% |
| Multinomial Naive Bayes | 97.58% | 88.37% |
| Bernoulli Naive Bayes | **97.87%** | **89.72%** |

For the final application, **Multinomial Naive Bayes** was used.

## 📊 Dataset

The dataset contains **5572 SMS messages**.

After removing **403 duplicate messages**, the final dataset contains **5169 messages**.

- 🟢 Ham: 4516
- 🔴 Spam: 653

## 🖥️ Desktop Application

A simple **Tkinter GUI** is included in the project.

The user can:
1. Enter an SMS message
2. Click **Predict**
3. Get the result as **Spam** or **Ham**

![Spam Detection GUI](spam_detection_gui.png)

## 💾 Saved Files

The following files are saved using Joblib:

- `Spam_Detection_Model`
- `Spam_Detection_Tfidf_Vectorizer`
- `Text Cleaning`

These files are used to make predictions on new messages without training the model again.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TF-IDF
- Matplotlib
- Seaborn
- WordCloud
- Joblib
- Tkinter

## 📌 Example

**Message:**

> Hey, just checking in to see how your day went. Want to grab coffee tomorrow?

**Prediction:** 🟢 **Ham Message**

## 👨‍💻 Project Summary

This project helped me understand the complete Machine Learning workflow for a text classification problem — from **data cleaning and NLP to model training, evaluation, model saving and GUI deployment**.
