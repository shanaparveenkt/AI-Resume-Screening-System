# 📄 AI Resume Screening & Skill Matching System

## 🧠 Overview
This project is an AI-powered Resume Screening System that analyzes and ranks resumes based on a given job description using Natural Language Processing (NLP) and transformer-based embeddings.

---

## 🎯 Objectives
- Automate resume screening and shortlisting
- Improve efficiency in recruitment
- Perform semantic matching instead of keyword matching

---

## ⚙️ Technologies Used
- Python  
- Sentence Transformers  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib  
- PyPDF2, python-docx  
- Streamlit (prototype UI)  

---

## 🚀 Features
- Supports PDF and DOCX resumes  
- Text preprocessing and normalization  
- Skill extraction with basic synonym handling  
- Semantic similarity using transformer embeddings  
- Candidate ranking based on similarity scores  
- Simple Streamlit interface for testing  

---

## 🧠 Methodology
1. Extract text from resumes  
2. Clean and preprocess text  
3. Extract relevant sections (skills, education, experience)  
4. Convert text into embeddings  
5. Compute cosine similarity between resume and job description  
6. Rank candidates based on similarity score  

---

## ▶️ How to Run

Install dependencies:
pip install -r requirements.txt

Run the application:
streamlit run app.py

---

## 📊 Output
- Ranked list of candidates  
- Similarity scores  
- Bar chart visualization  

---

## 💡 Future Improvements
- Advanced NLP-based skill extraction  
- Named Entity Recognition (NER)   

---

## 👩‍💻 Author
Shana Parveen KT
