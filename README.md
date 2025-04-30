# Movie-Recommendation-System

# 🎬 Movie Recommender System

A **Content-Based Movie Recommendation System** that intelligently suggests movies similar to a user’s chosen title by analyzing various aspects of movie metadata. This project demonstrates how data-driven recommendation engines work by leveraging movie features such as genres, keywords, cast, and crew details.

---

## 📖 Overview

Recommendation systems are at the heart of modern digital platforms like Netflix, YouTube, and Spotify, helping users discover new content tailored to their preferences. This project aims to replicate a simplified version of such systems using **content-based filtering** techniques on movie data.

The system computes the similarity between movies based on their metadata and suggests the most similar ones to the user’s selected film. It operates without user rating data, relying purely on the content attributes of each movie.

---

## 🎯 Objectives

- Build a working movie recommender system using **content-based filtering**.
- Learn to preprocess and engineer features from text-based metadata.
- Implement **cosine similarity** to measure movie-to-movie similarity.
- Deliver clean and meaningful movie recommendations within a Jupyter Notebook environment.

---

## 🔍 Methodology

1. **Data Preprocessing**
   - Load and inspect the dataset.
   - Merge and clean relevant metadata fields: genres, keywords, cast, crew, etc.
   - Select essential attributes that influence movie similarity.

2. **Feature Engineering**
   - Combine selected attributes into a single string for each movie.
   - Use **CountVectorizer** to convert text data into a numerical vector space.

3. **Similarity Calculation**
   - Apply **cosine similarity** to determine how closely related movies are based on their feature vectors.

4. **Recommendation Function**
   - Create a function that takes a movie title as input and returns the top 5 most similar movies.

---

## 🛠️ Tools & Libraries

- **Python 3**
- **Jupyter Notebook**
- `pandas` — data manipulation and analysis  
- `numpy` — numerical computing  
- `scikit-learn` — vectorization and similarity computations  

---

## 📂 Dataset

The project uses the **TMDb 5000 Movie Dataset**, which contains metadata for 5,000 movies including:
- Genres
- Cast and Crew
- Keywords
- Overview  

A great dataset for practicing recommendation system techniques.

---

## 📊 Results

The final system delivers a list of recommended movies based on their content similarity to a given movie. It works well for identifying films with similar themes, casts, genres, or plot elements.

---

## ⚠️ Limitations

- This is a **content-based recommender only** — it does not factor in user preferences or collaborative behavior.
- Limited to the quality and diversity of metadata available.
- It may recommend obscure or less popular titles if they have closely matching features.

---

## 💡 Possible Improvements

- Incorporating **TF-IDF Vectorizer** for weighting important keywords.
- Adding **Collaborative Filtering** for personalized recommendations.
- Integrating with a web-based front end for real-time user interaction.
- Enhancing feature extraction with movie overviews, director influence, or user ratings.

---

## 📌 Conclusion

This project provides a clear, hands-on demonstration of building a basic yet effective movie recommender system using content-based techniques. It serves as a great learning tool for anyone interested in recommendation engines, data science, and machine learning.

---

## 📜 License

This project is for educational purposes only.
