# Spam_Mail_Prediction_ML
Built a Spam Mail Detection system using Machine Learning with Python. Implemented text preprocessing and feature extraction using TF-IDF, followed by Logistic Regression for classification. The model effectively classifies emails as spam or ham with reliable accuracy.

# Spam Mail Detection using Logistic Regression

## Project Overview

This project implements a **Spam Mail Detection System** using Machine Learning with Python. The goal is to automatically classify emails as **Spam** or **Ham** based on their textual content. The system uses **TF-IDF vectorization** for feature extraction and **Logistic Regression** for classification.

---

## Features

* Text preprocessing and cleaning
* Label encoding of target classes
* Feature extraction using TF-IDF
* Logistic Regression model training
* Performance evaluation using accuracy
* Real-time email spam prediction

---

## Machine Learning Algorithm

* **Logistic Regression** – effective for binary classification problems like spam detection

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn

---

## Dataset

The dataset contains labeled email messages categorized as **Spam** or **Ham**. Null values are handled, and labels are encoded before training.

---

## Workflow

1. Import required dependencies
2. Load and preprocess the dataset
3. Encode target labels
4. Split data into training and testing sets
5. Extract features using TF-IDF Vectorizer
6. Train Logistic Regression model
7. Evaluate model accuracy
8. Build a predictive system for new emails

---

## Model Evaluation

* Accuracy is calculated on both training and test datasets to ensure model reliability.

---

## Predictive System

The trained model can predict whether a new email message is **Spam** or **Ham** based on its content.

---

## Conclusion

This project demonstrates an end-to-end machine learning pipeline for text classification and serves as a strong foundation for real-world spam detection systems.

---

## 📎 Future Improvements

* Add precision, recall, and F1-score evaluation
* Handle class imbalance more effectively
* Use n-grams and advanced NLP techniques

---

If you find this project useful, feel free to star the repository!
