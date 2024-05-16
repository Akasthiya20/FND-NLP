# Fake-News-Detection-using-NLP
This project aims to develop a fake news detection system using NLP techniques, focusing on labeled news articles classified as reliable or unreliable.
I have got the training and testing dataset from kaggle.
Preprocessing steps involve handling missing values, cleaning text data by removing special characters, converting to lowercase, tokenization, and stemming with NLTK. 
TF-IDF vectorization converts text into numerical vectors, capturing word importance. A Decision Tree Classifier is trained on preprocessed and vectorized data, evaluated using accuracy metrics, and saved using pickle.
 An interactive Streamlit web app allows users to input news content for real-time predictions, utilizing the saved model and vectorizer.This system provides a user-friendly interface to combat misinformation and ensure news credibility.
 By employing NLP techniques, the goal is to contribute to the development of effective tools for combating the spread of misinformation in online platforms.
