# Book Recommendation Engine

## Overview
This project is a collaborative filtering recommendation system built in Python. It analyzes user rating matrices to suggest reading material based on user preferences.

## Tools & Libraries Used
* **Python**
* **Pandas & NumPy** (Data manipulation and matrix operations)
* **Scikit-learn** (Cosine Similarity)
* **SciPy / SVD** (Singular Value Decomposition for dimensionality reduction)

## How It Works
1. Parses a large dataset of books and user ratings.
2. Creates a matrix of user-item interactions.
3. Uses Singular Value Decomposition (SVD) and Cosine Similarity to find the closest book matches based on previous reading history.
