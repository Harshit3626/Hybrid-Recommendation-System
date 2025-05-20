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

