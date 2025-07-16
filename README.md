# Movie_recommendation_system

<h1 align="center">🎬 Movie Recommendation System 🎥</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-ML%20Project-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-Recommendation-green?style=for-the-badge&logo=scikit-learn">
  <img src="https://img.shields.io/badge/Dataset-TMDB-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

---

## 📌 Overview

➤ This project implements a **Content-Based Movie Recommendation System** using metadata from **TMDB's 5000+ movies** dataset.

➤ The system suggests similar movies based on an input title using techniques such as **NLP-based feature extraction**, **vectorization**, and **cosine similarity**.

➤ Aimed at improving user experience on movie platforms, this is a great example of how machine learning can personalize content at scale.

---

## 🧠 Key Features

✔ Combine multiple features (genres, cast, crew, overview)  
✔ Clean and preprocess text for modeling  
✔ Transform text to vectors using `CountVectorizer`  
✔ Compute similarity using `cosine_similarity`  
✔ Return top 5 similar movie recommendations

---

## 🗃️ Dataset Info

Source: [TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)

Files used:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

Each movie entry contains:
- Title, Overview, Genre, Keywords  
- Cast, Crew (Director), Vote Stats, and more

---

## 🔧 Tools & Technologies

| Tool | Usage |
|------|-------|
| **Pandas** | Data manipulation and merging |
| **Scikit-learn** | Text vectorization, cosine similarity |
| **NumPy** | Array operations |
| **Python** | Core programming |
| *(Optional)* Streamlit | Build a live recommendation UI |

---

📈 Future Improvements
➤ Add a Streamlit UI for interactive movie search
➤ Implement collaborative filtering for more accurate results
➤ Include user ratings and feedback loop

👨‍💻 Author
Chirag Kaushik
Data Science | Machine Learning | Recommendation Systems
🔗 LinkedIn Profile : https://www.linkedin.com/in/chirag-kaushik-profile

📄 License
This project is for educational and personal learning purposes.
Data rights belong to TMDB and Kaggle dataset publishers.

