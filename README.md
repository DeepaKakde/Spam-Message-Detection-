# 📩 Spam Message Detection Using NLP

This is a Machine Learning project that predicts whether an SMS is **Spam** or **Ham (Normal Message)**.

### 🔹 What I did
- Loaded and cleaned the SMS dataset
- Removed duplicate messages
- Used **NLTK** for text cleaning
- Removed stopwords and special characters
- Used **TF-IDF** to convert text into numerical features
- Compared different **Naive Bayes** models
- Selected **Multinomial Naive Bayes** for the final application
- Saved the model using **Joblib**
- Created a simple **Tkinter GUI** for prediction

### 📊 Dataset
- Total messages: **5572**
- After removing duplicates: **5169**
- Ham: **4516**
- Spam: **653**

### 🤖 Model Results

| Model | Test Accuracy | F1 Score |
|---|---:|---:|
| GaussianNB | 80.85% | 51.71% |
| MultinomialNB | 97.58% | 88.37% |
| BernoulliNB | 97.87% | 89.72% |


### 🛠️ Technologies

**Python | Pandas | NumPy | NLTK | Scikit-learn | TF-IDF | Joblib | Tkinter | Matplotlib | Seaborn**


