# Amazon Product Recommendation System

This repository contains an academic project for building a product recommendation system using the Amazon Electronics product ratings dataset. The project was completed as part of the Data Science program at Great Learning, and coded in  Google Colab.

## Project Overview

The objective of this project is to develop and compare different recommendation system models to suggest products to Amazon users based on their previous ratings. The dataset consists of user ratings for various electronic products, without any product metadata or review text, to avoid bias.

## Key Steps

- **Data Preparation:**  
  - Loaded and cleaned the dataset, removing users and products with insufficient ratings.
  - Explored the data through summary statistics and visualizations.

- **Model Building:**  
  - Implemented a Rank-Based (popularity) recommendation system.
  - Built and evaluated collaborative filtering models:
    - User-User Similarity (KNN-based)
    - Item-Item Similarity (KNN-based)
    - Model-Based Collaborative Filtering (SVD matrix factorization)
  - Tuned hyperparameters for each model using grid search.

- **Evaluation:**  
  - Compared models using RMSE, Precision@k, Recall@k, and F1-score@k.
  - Provided recommendations for sample users and discussed model performance.

## Notes

- **Academic Project:**  
  This was an academic assignment, and some repetitive or manual tasks were performed as required by the instructions.
- The analysis and recommendations are for educational purposes and may not reflect real-world business constraints.

## Requirements

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- [scikit-surprise (surprise)](http://surpriselib.com/)
- Jupyter Notebook or Google Colab

## How to Run

1. Open the notebook `Robert Hilario Recommendation Systems.ipynb`.
2. Follow the cells in order to reproduce the analysis, modeling, and results.
3. For best compatibility with the `surprise` library, it is recommended to use Google Colab.

## Data

The dataset contains anonymized user ratings for electronic products on Amazon, including:
- `user_id`: Unique identifier for each user
- `prod_id`: Unique identifier for each product
- `rating`: User's rating for the product
- `timestamp`: (Not used in modeling)

---

**Author:** Robert Hilario  
**Institution:** Great Learning  
**Course:** Data Science  
**Project:** Recommendation System - Amazon Products