# 🎓 College Chatbot Application

An intelligent chatbot designed to assist students with college-related queries, tailored for **AIET** and **Alva's MBA College**. This chatbot blends classic machine learning with modern NLP and AI to provide fast, relevant answers through an easy-to-use web interface.

---

## 🚀 Project Overview

The chatbot supports dynamic question-answering by combining:

- **Machine Learning Models**:  
  - Decision Tree Classifier  
  - Hybrid Voting Classifier

- **Natural Language Processing (NLP)**:  
  - Lowercasing  
  - Stopword removal  
  - Stemming  

- **TF-IDF Vectorization**:  
  Converts text into numerical form for classification.

- **Semantic Similarity** using **Sentence Transformers (MiniLM)**:  
  Finds the most semantically similar answers.

- **Google Gemini (Generative AI)**:  
  Summarizes lengthy answers into concise, readable outputs.

- **Streamlit**:  
  Builds the user-friendly interface to chat with the system.

---

## ✨ Features

- Accurate and relevant college-related answers  
- Smart response summarization via Gemini  
- Hybrid classification and semantic retrieval  
- Dataset handling for AIET and Alva's MBA College  
- Clean UI using Streamlit

---

## 🛠️ Tech Stack

- Python  
- Scikit-learn  
- NLTK / SpaCy  
- SentenceTransformers (MiniLM)  
- Streamlit  
- Google Gemini API  
- Pandas, NumPy

---

## ⚙️ Running the App

1. Install Dependencies
pip install -r requirements.txt
2. Run the Application
python -m streamlit run a1.py
