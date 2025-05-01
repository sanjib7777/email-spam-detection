# 📧 Email Spam Detection with Machine Learning

A simple machine learning project to detect whether an email is spam or not using natural language processing and logistic regression.

---

## 🚀 Project Overview

This project uses a dataset of labeled emails to train a machine learning model that classifies emails as **"spam"** or **"not spam"**. The model is trained using scikit-learn, vectorized using `TfidfVectorizer`, and deployed using a Flask web app.

---

## 🧠 Features

- Text preprocessing and cleaning
- TF-IDF vectorization
- Logistic Regression classifier
- Model persistence with `pickle`
- Flask-based deployment (`app.py`)
- Interactive UI for real-time email classification

---

## 📁 Repository Structure

```bash
email-spam-detection/
│
├── app.py                        # Flask app for deployment
├── email-spam-detection.ipynb   # Jupyter notebook with EDA + model training
├── email.csv                    # Email dataset used for training
├── model.pkl                    # Trained spam detection model
├── vectorizer.pkl               # TF-IDF vectorizer used with the model
├── requirements.txt             # List of dependencies
└── .ipynb_checkpoints/          # Jupyter auto-generated folder

```
## Clone the Repo
```
git clone https://github.com/sanjib7777/email-spam-detection.git
cd email-spam-detection

