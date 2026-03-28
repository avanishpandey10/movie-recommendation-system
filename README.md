# 🎬 Movie Recommendation System

A smart Movie Recommendation System built using **Content-Based Filtering** that suggests movies based on similarity in content like genres, overview, and keywords.

---

## 🚀 Overview

This project recommends movies by analyzing their content and finding similar movies.  
It is trained on a dataset of **45,000+ movies** and delivers personalized recommendations.

---

## ✨ Features

- 🔍 Movie search with autocomplete suggestions  
- 🎯 Content-based recommendations  
- 📊 Trained on **45,000+ movie dataset**  
- 🖼️ Movie posters & details using **TMDB API**  
- ⚡ Fast backend using **FastAPI**  
- 🎨 Interactive UI using **Streamlit**  
- 🌐 Deployed on **Render (Backend)** & **Streamlit Cloud (Frontend)**  

---

## 🧠 How It Works

- Combines movie metadata (**genres, overview, keywords**)  
- Converts text into vectors using **TF-IDF Vectorization**  
- Computes similarity using **Cosine Similarity**  
- Recommends top similar movies based on scores  

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** FastAPI  
- **Machine Learning:** Scikit-learn (TF-IDF, Cosine Similarity)  
- **Data Processing:** Pandas, NumPy  
- **API Integration:** TMDB API  
- **Deployment:** Render & Streamlit Cloud  

---

## 📂 Project Structure
movie-recommendation-system/
│── main.py # FastAPI backend
│── app.py # Streamlit frontend
│── model.pkl # ML model
│── data.pkl # Processed dataset
│── requirements.txt
│── README.md
