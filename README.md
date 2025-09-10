# Machine Learning Projects Portfolio

This repository contains practical implementations of fundamental machine learning concepts and algorithms.

## 📂 Projects

### 1. Customer Segmentation using K-Means Clustering
**Location:** `/Customer-Segmentation/`

This project segments a company's customer base into distinct groups based on their purchasing behavior. The goal is to identify patterns to drive targeted marketing strategies.

**Key Steps:**
- Data Preprocessing & Exploratory Data Analysis (EDA)
- Feature Scaling (StandardScaler)
- Determining the optimal number of clusters using the Elbow Method
- Applying K-Means Clustering
- Analyzing and visualizing the customer segments

**Technologies:** `Python`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`

---

### 2. Movie Rating Prediction using Collaborative Filtering
**Location:** `/Movie-Rating-Prediction/`

This project builds a recommendation system to predict user ratings for movies they haven't seen. It uses collaborative filtering techniques to find similarities between users and items.

**Key Steps:**
- Loading and exploring the MovieLens (or similar) dataset
- Handling missing values and creating a user-item matrix
- Implementing a model-based (SVD) or memory-based (KNN) collaborative filtering approach
- Evaluating model performance using RMSE (Root Mean Squared Error)

**Technologies:** `Python`, `pandas`, `scikit-learn`, `scikit-surprise`, `matplotlib`
