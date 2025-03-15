

# 🎬 Netflix Movie Recommendation System

## 📌 Project Overview
This project is a **Content-Based Movie Recommendation System** that suggests movies based on user input. It leverages **Natural Language Processing (NLP)** techniques to analyze movie genres, keywords, cast, and directors to provide accurate and personalized recommendations.

---

## 🚀 How Does It Work?
- The system takes the **movie name as input from the user.**
- It **extracts key features like genres, cast, tagline, and overview** from the dataset.
- Using **TF-IDF Vectorization**, it converts the text data into numerical format.
- With **Cosine Similarity**, it finds the movies that are most similar to the user's favorite movie.
- Finally, it recommends the **top 30 similar movies** based on relevance.

---

## 🔧 Technologies Used
✅ Python  
✅ Pandas & NumPy  
✅ TF-IDF Vectorizer  
✅ Cosine Similarity  
✅ Machine Learning Concepts  

---

## 📂 Dataset Used
The dataset `movies.csv` consists of movie-related information such as:  
🎬 Movie Title  
🎭 Cast & Crew  
📌 Genres  
🎬 Director  
📝 Overview  

---

## 🎯 Key Features
✅ Recommend Similar Movies  
✅ Handles Missing Data  
✅ Content-Based Filtering  
✅ Fast and Accurate  

---

## 🛠️ How to Run the Project?
1️⃣ Clone the repository  
```bash
git clone https://github.com/Kirthick-2001/Netflix-Recommendation-System.git
```
2️⃣ Install the required libraries  
```bash
pip install pandas numpy scikit-learn
```
3️⃣ Run the Python file  
```bash
python netflix_recommendation_rystem.py
```
4️⃣ Enter your favorite movie name, and get suggestions instantly!  

---

## 🎯 Sample Output
```
ENTER YOUR FAVORITE MOVIE NAME: Avatar

SUGGESTED MOVIES TO WATCH ARE:
1. Avatar  
2. Guardians of the Galaxy  
3. Avengers: Infinity War  
4. Star Wars: The Force Awakens  
5. Interstellar  
...
```

---

## 🌟 What I Learned
✅ How to handle text data  
✅ Feature engineering with TF-IDF  
✅ Building a recommendation system from scratch  
✅ Improving accuracy with Cosine Similarity  

