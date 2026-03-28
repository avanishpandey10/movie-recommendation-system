# 🎬 Movie Recommendation System

A Machine Learning web application that recommends movies based on similarity using **Content-Based Filtering**.  
The system suggests movies by analyzing genres, overview, and keywords.

---

## 🚀 Live Features

* 🔍 Search any movie بسهولة  
* 🎯 Get similar movie recommendations  
* 📊 Trained on **45,000+ movies dataset**  
* 🖼️ Fetch movie posters using **TMDB API**  
* ⚡ Fast API backend using **FastAPI**  
* 🎨 Interactive UI with **Streamlit**

---

## 🧠 Machine Learning Workflow

Movie Input  
⬇  
Data Preprocessing (Genres, Overview, Keywords)  
⬇  
TF-IDF Vectorization  
⬇  
Cosine Similarity Calculation  
⬇  
Top Recommended Movies  

---

## 🛠 Technologies Used

* Python  
* Streamlit  
* FastAPI  
* Scikit-Learn  
* Pandas  
* NumPy  
* Pickle  
* TMDB API  

---

## 📂 Project Structure

movie-recommendation-system/
│
├── app.py # Streamlit frontend
├── main.py # FastAPI backend
├── df.pkl # Processed dataset
├── tfidf.pkl # TF-IDF model
├── tfidf_matrix.pkl # Vectorized data
├── indices.pkl # Movie index mapping
├── requirements.txt
└── README.md


---

## ⚙️ Installation

Clone the repository:
https://github.com/avanishpandey10/movie-recommendation-system.git

Navigate to project folder:
cd movie-recommendation-system

Install dependencies:
pip install -r requirements.txt

---

## ▶️ Run the Application

### Start Backend (FastAPI)
uvicorn main:app --reload

### Start Frontend (Streamlit)

streamlit run app.py

Then open browser:

http://localhost:8501

---

## 🌐 Deployment

* Frontend: Streamlit Cloud  
* Backend: Render  

---

## 📊 Dataset

Trained on a dataset of **45,000+ movies**, including metadata like genres, overview, and keywords.

---

## 📸 Output Screenshot

![Home](images/home.png)
![Recommendation](images/recommend.png)

project live:
https://movie-recommendation-system10.streamlit.app/

## 📌 Future Improvements

* Add collaborative filtering  
* Improve recommendation accuracy  
* Add user login system  
* Deploy full-stack integration  
* Add rating-based recommendations  

---
---

## 👨‍💻 Author
**Avanish Pandey**  

LinkedIn:  
https://www.linkedin.com/in/avanish-pandey-976b76253/

---

## 📜 License

This project is for educational and portfolio purposes.  
© 2026 Avanish Pandey
