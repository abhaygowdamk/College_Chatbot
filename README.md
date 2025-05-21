# 🎓 Alva's Chatbot Application

This is an intelligent chatbot application built specifically for college-related queries. It is designed to provide accurate, context-aware answers to students using a blend of traditional machine learning and cutting-edge AI technologies.

---

## 🚀 Project Overview

This chatbot system helps students of **AIET** and **Alva's MBA College** get instant responses to their queries using:

- **Machine Learning Models**:  
  - Decision Tree Classifier  
  - Hybrid Voting Classifier (for improved accuracy and robustness)

- **Natural Language Processing (NLP)**:  
  - Text cleaning and normalization  
  - Lowercasing  
  - Stopword removal  
  - Stemming  

- **TF-IDF Vectorization**:  
  Used for transforming text into numerical vectors for classification and similarity matching.

- **Semantic Search** using **Sentence Transformers (MiniLM)**:  
  Retrieves answers based on semantic similarity, enabling smarter and more human-like understanding of queries.

- **Google Gemini (Generative AI)**:  
  Summarizes lengthy responses into concise answers for better user experience.

- **Streamlit**:  
  Used for building the interactive web-based UI.

---

## ✨ Features

- Accurate and fast responses to college-related questions  
- Hybrid ML + Semantic Search pipeline  
- Real-time response summarization using Gemini  
- Streamlit-based UI for ease of use  
- Separate dataset handling for two colleges: AIET and Alva's MBA College

---

## 🛠️ Tech Stack

- Python  
- Scikit-learn  
- NLTK / SpaCy  
- SentenceTransformers  
- Streamlit  
- Google Gemini API  
- Pandas, NumPy

---

### 1. Install Dependencies
```bash
pip install -r requirements.txt

---

### 2. Run the Application
```bash
python -m streamlit run a1.py
