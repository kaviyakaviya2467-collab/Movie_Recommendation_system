# Movie_Recommendation_system

# 🎬 Movie Recommendation System

## 📌 Overview

An AI-powered **Movie Recommendation System** that recommends movies based on a user's recently watched movies. The project uses NLP techniques to understand movie information and find similar movies.

## 🎯 Objective

To build a personalized recommendation system and compare different NLP-based approaches to identify the model that provides better recommendations.

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* Gensim
* Word2Vec
* Sentence Transformers
* Cosine Similarity
* Gradio

## 🔄 Workflow

1. Load and preprocess movie data
2. Combine movie title, genres, and overview
3. Generate Word2Vec embeddings
4. Generate Sentence Transformer embeddings
5. Calculate cosine similarity
6. Generate movie recommendations
7. Evaluate and compare model performance
8. Display recommendations using Gradio

## 📊 Model Performance

| Model                | Success Rate |
| -------------------- | -----------: |
| Previous Model       |       13.85% |
| Word2Vec             |       22.70% |
| Sentence Transformer |   **64.75%** |

## 🚀 Result

The **Sentence Transformer** model performed best with a **64.75% success rate**, providing more relevant recommendations compared with the other approaches.

