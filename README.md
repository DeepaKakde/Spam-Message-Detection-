# Spam Message Detection

## About Project

This is my Machine Learning project for detecting spam messages.

In this project, I used SMS messages and trained a machine learning model to identify whether a message is **Spam** or **Not Spam**.

I used **NLP** for cleaning the text and **TF-IDF** to convert the text into numerical values. After that, I trained the model and used it to predict new messages.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* NLP
* TF-IDF
* Jupyter Notebook

## Dataset

I used an SMS dataset which contains two types of messages:

* Spam
* Ham (Not Spam)

## Working

The project works in these steps:

1. Load the SMS dataset.
2. Clean the text messages.
3. Convert text into numbers using TF-IDF.
4. Train the machine learning model.
5. Test the model.
6. Give a prediction for a new message.

## Example

Input:

`Congratulations! You have won a free prize.`

Output:

`Spam`

Input:

`Hey, are you free tomorrow?`

Output:

`Not Spam`

## Files in this Project

* `Spam Detection.ipynb` - Main notebook
* `spam_ham.txt` - Dataset
* `Spam_Detection_Model` - Saved machine learning model
* `Spam_Detection_Tfidf_Vectorizer` - Saved TF-IDF vectorizer
* `Text Cleaning` - Text cleaning file

## Conclusion

This project helped me understand how **Machine Learning and NLP** can be used for text classification. I also learned how to clean text, use TF-IDF, train a model and make predictions.


