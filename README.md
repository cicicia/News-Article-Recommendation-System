# News Article Recommendation System

This project implements a simple **content-based recommendation system** for news articles using **TF-IDF vectorization** and **cosine similarity**. The system recommends similar news articles based on the headline and short description text.

## Dataset
The project uses the [News Category Dataset](https://www.kaggle.com/rmisra/news-category-dataset) from Kaggle, which contains over 200,000 news articles categorized into various topics.

## Features
- Text preprocessing: cleaning, lowercasing, punctuation removal, stopword removal
- Vectorization using TF-IDF (max 5000 features)
- Similarity calculation with cosine similarity matrix
- Recommendation function to get top-N similar articles given an article index
- Easy to adapt for other text datasets

## Usage
1. Load and preprocess the dataset.
2. Compute TF-IDF vectors from cleaned text.
3. Compute cosine similarity matrix.
4. Use the `recommend_articles(article_index, top_n)` function to get recommended articles similar to the selected one.

Example:
```python
recommend_articles(10, top_n=5)
