# 🎬 MovieLens Collaborative Filtering Recommendation System

> A personalized movie recommendation system built using **User-Based Collaborative Filtering**, **User-Item Rating Matrices**, and **Cosine Similarity** on the MovieLens dataset.

---

## 📌 Project Overview

Recommendation systems are an important application of Machine Learning that help users discover relevant content based on their previous interactions and preferences.

This project develops a **movie recommendation system using collaborative filtering**. It analyzes historical user-movie ratings, constructs a User-Item Rating Matrix, identifies users with similar rating patterns using Cosine Similarity, and generates personalized movie recommendations.

The project demonstrates the complete workflow of building a recommendation system from real-world user-item interaction data.

---

## 🎯 Project Objective

The primary objective of this project is to develop a **User-Based Collaborative Filtering recommendation system** capable of:

- Building a User-Item Rating Matrix from MovieLens data.
- Understanding user-movie interactions.
- Analyzing the sparsity of the rating matrix.
- Measuring similarity between users using Cosine Similarity.
- Identifying users with similar movie preferences.
- Generating personalized Top-N movie recommendations.
- Performing rating prediction based on similar users.

---

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| 🐍 **Python** | Core programming language |
| 🐼 **Pandas** | Data loading and manipulation |
| 🔢 **NumPy** | Numerical and matrix operations |
| 🤖 **Scikit-learn** | Similarity computation and ML utilities |
| 📊 **Matplotlib** | Data visualization |
| 📈 **Seaborn** | Statistical visualization |
| ☁️ **Google Colab** | Development and experimentation |
| 🐙 **GitHub** | Project hosting and version control |

---

## 📊 Dataset

This project uses the **MovieLens dataset provided by GroupLens Research**.

The dataset contains historical movie ratings provided by users along with movie metadata.

### Key Attributes

- **User ID** – Unique identifier of a user.
- **Movie ID** – Unique identifier of a movie.
- **Rating** – Rating given by a user to a movie.
- **Timestamp** – Time at which the rating was recorded.
- **Movie Information** – Movie titles and genres.

> **Note:** The raw MovieLens dataset is not included in this repository.

---

## 🔄 Project Workflow

```text
              MovieLens Dataset
                     │
                     ▼
          Data Loading & Exploration
                     │
                     ▼
            Data Preprocessing
                     │
                     ▼
          User-Item Rating Matrix
                     │
                     ▼
             Sparsity Analysis
                     │
                     ▼
             Cosine Similarity
                     │
                     ▼
          Similar User Identification
                     │
                     ▼
       User-Based Collaborative Filtering
                     │
                     ▼
          Top-N Movie Recommendations
                     │
                     ▼
             Rating Prediction

                     ▼
              Results & Analysis
