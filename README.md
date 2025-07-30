# 📚 Book Recommender System

This project builds a simple but effective **Book Recommender System** using both **Content-Based Filtering** and **Collaborative Filtering**. A hybrid approach is also implemented to improve recommendations.

## 🔍 Features

- ✅ **Content-Based Filtering** using TF-IDF on book metadata (`Title`, `Author`, `Genre`)
- ✅ **Collaborative Filtering** based on user ratings using cosine similarity
- ✅ **Hybrid Recommendation** combining both methods
- ✅ Interactive visualizations using `Seaborn` heatmaps
- ✅ Easy-to-understand and extendable Jupyter notebook format

## 📂 Files Included

- `Book_Recommender_System.ipynb` – Main notebook containing the complete analysis and models
- `books.csv` – Dataset with book details like title, author, and genre
- `ratings.csv` – User ratings for books

## 📦 Libraries Used

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## 🧠 How It Works

1. **Content-Based Filtering**  
   Recommends books similar in content (e.g., genre, author) using TF-IDF and cosine similarity.

2. **Collaborative Filtering**  
   Uses user ratings to find similar users and recommend what those users liked.

3. **Hybrid Approach**  
   Combines both methods using a weighted score for better accuracy.


