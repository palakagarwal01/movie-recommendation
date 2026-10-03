# 🎬 movie-recommender: Content-Based Movie Recommendation System

**movie-recommender** is an unsupervised Machine Learning system that suggests top-rated movies based on user preferences. By utilizing vector-space geometry, the model generates recommendations by analyzing textual data links like synopses, structural genres, production keywords, lead cast members, and directing crews.

## 🛠️ Tech Stack & Mathematical Concepts
* **Language:** Python (Google Colab Environment)
* **Dataset:** TMDB 5000 Movies Matrix Distribution
* **NLP Processing:** **CountVectorizer (Bag-of-Words)** transforming merged text corpuses into high-dimensional numerical vector indices.
* **Similarity Metric Engine:** **Cosine Similarity** computing spatial angles between coordinate vectors:
  \[\text{Similarity}(A, B) = \frac{A \cdot B}{\Vert{}A\Vert{} \Vert{}B\Vert{}}\]

## 🚀 How to Run
1. Open the repository notebook via the blue **"Open in Colab"** badge.
2. Upload the raw `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv` files.
3. Run the notebook blocks sequentially and call the `recommend("Movie Name")` function loop interface.
