# 🎬 Movie Recommender System using Deep Learning

This project implements a **Movie Recommender System** using **deep learning** with **Keras** and the **MovieLens 100K dataset**. The recommender is built using **collaborative filtering** through **matrix factorization with embedding layers**.

## 📂 Dataset

- Dataset: [MovieLens 100K](https://grouplens.org/datasets/movielens/100k/)
- Contains 100,000 ratings from 943 users on 1682 movies.

## 🧠 Model Architecture

- User and movie **embedding layers**
- Dot product of embeddings to estimate ratings
- Dense layer for refinement
- Trained using Mean Squared Error (MSE) loss

## 🚀 How to Run

1. Clone the repository or download the Jupyter notebook.
2. Open the notebook: `movie_recommender_deep_learning.ipynb`
3. Run all cells sequentially:
    - Downloads and unzips the MovieLens dataset
    - Preprocesses user and movie data
    - Builds and trains a deep learning model
    - Evaluates the model and recommends top N movies

## 📦 Requirements

- Python 3.x
- pandas, numpy, matplotlib
- scikit-learn
- keras, tensorflow

Install dependencies with:

```bash
pip install -r requirements.txt
```

## 📊 Evaluation

- MSE and RMSE metrics are used to evaluate model accuracy on test data.

## 🔍 Sample Output

Recommends top N movies for a selected user based on predicted ratings.

## 📌 To Improve

- Add user/movie bias terms
- Add genre/content-based hybrid features
- Introduce deeper layers for learning nonlinear relationships

---

Created with Tension using Keras and TensorFlow.
