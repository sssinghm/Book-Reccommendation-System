
#Book Recommendation System
This project implements a collaborative filtering-based Book Recommendation System using the Book-Crossing dataset. The system recommends books to users based on similar reading preferences of other users.

##Key Features
Cleaned and filtered user ratings to include active users and popular books

Focused on US and Canada users for region-specific recommendations

Built a user-item matrix and applied K-Nearest Neighbors (KNN) using cosine similarity

Provided real-time book suggestions with author details

Visualized data distribution using histograms

##Technologies Used
Python, Pandas, NumPy

Scikit-learn (KNN)

Matplotlib

SciPy (sparse matrix)

##How It Works
Load and preprocess data (books, ratings, users)

Create a pivot table (books x users)

Train a KNN model to find similar books

Recommend books based on nearest neighbors


