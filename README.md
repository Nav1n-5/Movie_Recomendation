# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built using **Python**, **scikit-learn**, and **Streamlit**, and deployed via **Heroku**.

This system recommends movies similar to the one you input, based on metadata such as genres, cast, crew, keywords, and more.

---



## 🔍 Features

- ✅ Recommends 5 similar movies based on your input
- ✅ Uses NLP techniques to process and vectorize movie metadata
- ✅ Cosine similarity to calculate closeness between movies
- ✅ Streamlit UI for fast and interactive user experience
- ✅ Fully deployed and accessible online via Heroku

---

## 🛠️ How It Works

1. **Data Cleaning & Merging**: Combines movie metadata such as genres, cast, keywords, and overview into a single text column (`tags`).
2. **Vectorization**: Uses `CountVectorizer` to convert text into numerical vectors.
3. **Similarity Computation**: Computes a similarity matrix using **Cosine Similarity**.
4. **Recommendation Function**: When a user inputs a movie title, the app finds the top 5 most similar movies.

---

## 🧪 Technologies Used

| Category        | Tech                     |
|----------------|--------------------------|
| Programming     | Python                   |
| Libraries       | Pandas, scikit-learn, Numpy |
| Web App         | Streamlit                |
| Deployment      | Heroku                   |

---



## 🚀 Getting Started Locally

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/movie-recommender.git
cd movie-recommender
