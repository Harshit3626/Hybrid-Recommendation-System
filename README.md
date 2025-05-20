# 🎬 Hybrid Movie Recommendation System

A hybrid movie recommender system built using **TF-IDF content-based filtering** and **SVD-based collaborative filtering**, developed in a **Google Colab Notebook**. The system uses a cleaned and preprocessed movie dataset sourced from **Kaggle**.

---

## 📁 Project Overview

This project combines both **content-based** and **collaborative filtering** techniques to provide robust movie recommendations tailored to individual user preferences.

- 📌 **Content-Based Filtering**: Recommends movies similar in description/genre to a movie the user likes.
- 📌 **Collaborative Filtering**: Recommends movies based on what similar users have liked using **SVD (Singular Value Decomposition)**.

Implemented in a single notebook: **`Project code.ipynb`**  
Dataset used: **`final_dataset.csv`**

---

## 🛠️ Setup Instructions

To run the notebook:

1. Upload `final_dataset.csv` and `Project code.ipynb` to your Colab environment.
2. Install required libraries:

```bash
pip install fuzzywuzzy
pip install scikit-surprise


Dataset
Source: Kaggle (final_dataset.csv)

Contains preprocessed movie metadata including:

Movie titles

Genres

Tags/descriptions

User ratings

This dataset is already cleaned and formatted for direct use in both content-based and collaborative recommendation models.

🤖 Models Used
🔍 Content-Based Filtering
Technique: TF-IDF Vectorization

Similarity Measure: Cosine Similarity

Goal: Recommend movies similar in content to a given movie.

👥 Collaborative Filtering
Technique: Matrix Factorization using SVD from the Surprise library

Goal: Recommend movies liked by users with similar taste profiles.

🧪 How It Works
User Inputs:

A user ID

A favorite movie title

System Generates:

🎯 Content-based recommendations based on TF-IDF similarity

🤝 Collaborative recommendations based on SVD predictions

✅ Merged hybrid list that combines both

📊 Sample Output
Content-Based: Suggests movies similar in description/genre to the selected movie.

Collaborative Filtering: Suggests what similar users also enjoyed.

Hybrid Result: Combines both insights for personalized, relevant recommendations.


