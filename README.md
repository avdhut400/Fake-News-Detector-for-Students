🎓 Fake News Detector for Students

A Machine Learning–based web application that helps students identify whether a news article or message is Fake, Real, or Uncertain, especially for education-related content like exams, jobs, scholarships, and viral social media messages.

📌 Problem Statement

Students are frequently exposed to fake or misleading news through social media and messaging platforms.
Such misinformation can cause confusion, panic, and wrong decisions regarding exams, admissions, or jobs.

💡 Solution

This project uses Natural Language Processing (NLP) and Machine Learning to analyze news text and predict its authenticity based on learned language patterns.

The system provides:

✅ REAL News

❌ FAKE News

🤔 UNCERTAIN (Needs Verification)

instead of forcing incorrect predictions.

🚀 Features

📰 Detects fake and real news with confidence scores

🎯 Probability-based prediction logic

🎓 Focused on student-related news

🌐 Interactive Streamlit web interface

⚠️ Warns users when verification is required

🧠 Tech Stack

Python

Scikit-learn

Natural Language Processing (NLP)

Streamlit

Pickle

⚙️ How It Works

User enters news text

Text is cleaned using NLP techniques

Vectorizer converts text into numerical form

Trained ML model predicts probabilities

Final decision is shown based on confidence threshold

📂 Project Structure
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md

▶️ Run Locally
pip install -r requirements.txt
streamlit run app.py

🎯 Prediction Logic

Fake ≥ 60% → ❌ Fake News

Real ≥ 60% → ✅ Real News

Otherwise → 🤔 Uncertain / Needs Verification

⚠️ Disclaimer

This tool predicts the likelihood of misinformation based on trained data and language patterns.
It does not replace official fact-checking sources.

👨‍🎓 Author

Avdhut
Student | Machine Learning & Web Development Enthusiast
