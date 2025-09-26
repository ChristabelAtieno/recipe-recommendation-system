# Hybrid Recipe Recommendation System

## Project Overview
This project implements a **hybrid recipe recommendation system** that combines **collaborative filtering (CF)** and **content-based filtering (CBF)**. The system is designed to provide **personalized recipe recommendations** to users based on their past ratings and the content of recipes. Additionally, nutritional information is incorporated to allow for **health-aware recommendations**.

---

## Features
- **Collaborative Filtering (CF):**  
  Predicts user preferences based on patterns in other users’ ratings using **SVD (matrix factorization)**.
  
- **Content-Based Filtering (CBF):**  
  Uses recipe textual features such as `Description`, `Keywords`, and `Ingredients` to recommend recipes similar to ones the user likes.

- **Hybrid Recommendations:**  
  Combines CF and CBF to provide recommendations that are both **personalized** and **content-aware**.

---
