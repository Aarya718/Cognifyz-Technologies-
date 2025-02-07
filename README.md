# Cognifyz-Technologies-

Name - Aarya Ramchandra Tarphe 

Internship date - 5th February to 5th March 

Postion - Machine Learning Intern 

# TASK 1 - Restaurant Recommendation System

This project builds a content-based restaurant recommendation system that suggests restaurants based on user preferences for cuisine type and price range.

This project builds a **content-based restaurant recommendation system** using **cuisine preference and price range**.  

- **Step 1: Load Dataset** – Reads restaurant data from a CSV file.  

- **Step 2: Data Cleaning** – Drops irrelevant columns, handles missing values, encodes categorical features, and normalizes numerical data.  

- **Step 3: Data Visualization** – Generates **five** key plots: rating distribution, restaurant count by price range, cost boxplot, votes vs. rating scatterplot, and correlation heatmap.  

- **Step 4: Feature Engineering** – Uses **TF-IDF vectorization** on cuisine types.  

- **Step 5: Compute Similarity Matrix** – Calculates **cosine similarity** between restaurants based on cuisine.  

- **Step 6: Recommendation System** – Matches user inputs (cuisine, price range) to find and rank similar restaurants.  

- **Step 7: Testing** – Provides sample recommendations for a given cuisine and price range.

  # TASK 2 -  Cuisine Classification
  
This project builds a machine learning model to classify restaurants based on their cuisines.  

This project develops a cuisine classification model using restaurant data, focusing on data preprocessing, visualization, and model evaluation.  

### **Steps:**  
- **Step 1: Load Dataset** – Reads restaurant data from a CSV file.
  
- **Step 2: Data Cleaning** – Handles missing values, merges rare cuisines, and encodes categorical variables.
 
- **Step 3: Data Visualization** – Generates key plots: cuisine distribution, rating histogram, cost distribution, correlation heatmap, and class imbalance check.  

- **Step 4: Feature Engineering** – Applies one-hot encoding to cuisines and normalizes numerical features.  

- **Step 5: Train-Test Split** – Splits the dataset into training and testing sets.  

- **Step 6: Model Training** – Trains a classifier (Random Forest/XGBoost) with class balancing techniques.  

- **Step 7: Model Evaluation** – Computes accuracy, precision, recall, and F1-score with `zero_division=1` to handle undefined metrics.  

- **Step 8: Address Class Imbalance** – Uses **SMOTE** to oversample minority cuisines and improves classification performance.  

- **Step 9: Testing** – Predicts cuisines for sample restaurants and analyzes misclassified cases.  

