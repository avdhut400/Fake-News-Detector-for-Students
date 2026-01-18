# 🎓 Fake News Detector for Students

A machine learning–based web application that helps students identify **fake, real, or uncertain news** related to **education, exams, jobs, and viral academic messages**.  
The application is built using **Python, NLP, Machine Learning, and Streamlit**.

---

## 🚀 Project Overview

With the rapid spread of misinformation on social media, students often face confusion regarding exams, results, scholarships, and job opportunities.  
This project aims to provide a simple tool that analyzes textual news content and predicts whether it is:

- ❌ Fake  
- ✅ Real  
- 🤔 Uncertain (needs verification)

---

## 🧠 How It Works

1. User pastes education-related news text into the app  
2. Text is cleaned using NLP preprocessing  
3. A trained ML model predicts probabilities for:
   - Fake news
   - Real news
4. Final decision is made using a **60% confidence threshold**

> ⚠️ **Disclaimer:**  
> This system predicts the likelihood of misinformation based on language patterns.  
> It does **not replace official fact-checking sources**.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** (Web UI)
- **Scikit-learn**
- **Natural Language Processing (NLP)**
- **Pickle** (Model & Vectorizer storage)

---

## 📊 Dataset

- The dataset used to train this model is **sourced from Kaggle**
- It focuses on **education-related news**
- Initially, US-based datasets were explored, but the final training was done using **India-related education news data from Kaggle**

> Dataset Source: **Kaggle (Indian education-related dataset)**

---

## 🎯 Model Output Logic

- **Fake** → Fake probability ≥ 60%
- **Real** → Real probability ≥ 60%
- **Uncertain** → If neither crosses 60%

---

## 🖥️ Application Features

- Simple and clean UI
- Real-time prediction
- Confidence score display
- Handles ambiguous cases as *Uncertain*
- Designed specifically for **students**

---

## ▶️ How to Run Locally

```bash
# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
