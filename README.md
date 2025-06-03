# News-Article-Recommendation-System
News Article Recommendation System This project implements a simple content-based recommendation system for news articles using TF-IDF vectorization and cosine similarity. It recommends similar news articles based on the headline and short description text.

Features
  - Text preprocessing (cleaning, stopword removal)
  - Vectorization using TF-IDF (max 5000 features)
  - Similarity calculation with cosine similarity
  - Recommend top-N similar articles given a selected article index
  - Works on News Category Dataset (Kaggle)

Usage
  - Load and preprocess data
  - Compute TF-IDF vectors and cosine similarity matrix
  - Call the recommend_articles() function with the article index to get recommendations

Future improvements
  - Use transformer-based embeddings (e.g. Sentence-BERT) for better semantic understanding
  - Add a web interface for easier interaction (e.g. Streamlit)
  - Implement filtering by categories
