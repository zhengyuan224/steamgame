# Steam Game Recommendation System 

This project involves the analysis of Steam game data and the development of a recommendation system. It utilizes user purchase history and reviews to understand user behavior and potentially recommend items.

## Dataset
The project uses the following datasets:
- `australian_users_items.json`: Contains information about items purchased by users.
- `australian_user_reviews.json`: Contains user reviews for games.

## Requirements
The following Python libraries are used in this project:
- `numpy`
- `pandas`
- `scipy`
- `sklearn`
- `torch` (PyTorch)
- `matplotlib`
- `tqdm`

## Usage
The main analysis and code are contained in the Jupyter Notebook:
- `recommend system.ipynb`

To run the project, ensure you have the required dependencies installed and run the notebook cells sequentially.

## Features
- Data loading and parsing from JSON files.
- Exploratory Data Analysis (EDA) on user purchases and reviews.
- Implementation of various models for recommendation and classification:
    - **Machine Learning**: Linear Model (Logistic Regression), Naive Bayes (GaussianNB), Random Forest.
    - **Deep Learning**: Deep Neural Network (DNN) using PyTorch.
    - **Collaborative Filtering**: User-based similarity using Jaccard index, and Matrix Factorization using SVD++ (Surprise library).
