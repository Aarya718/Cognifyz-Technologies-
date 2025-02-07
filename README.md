# Cognifyz-Technologies-
Name - Aarya Ramchandra Tarphe 
Internship date - 5th February to 5th March 
Postion - Machine Learning Intern 

Overview of the Restaurant Recommendation System

This project builds a content-based restaurant recommendation system that suggests restaurants based on user preferences for cuisine type and price range.

Step 1: Load Dataset
Reads restaurant data from a CSV file.

Step 2: Data Cleaning
Sub-Steps:
Remove Irrelevant Columns

Drops columns that are unnecessary for recommendations, such as Restaurant ID, Address, and Longitude.
Handle Missing Values

Fills missing values in categorical columns (Cuisines, Price range) with the mode.
Replaces missing values in numerical columns (Aggregate rating) with the median.
Sets missing vote counts to 0.
Encode Categorical Features

Converts categorical columns (Has Table booking, Has Online delivery, etc.) into numerical values using LabelEncoder.
Normalize Numerical Features

Scales Average Cost for two, Votes, and Aggregate rating using StandardScaler to ensure fair comparisons.

Step 3: Data Visualization
Includes 4 Key Plots:
Histogram of Restaurant Ratings
Shows the distribution of restaurant ratings.
Countplot of Restaurants by Price Range
Displays the number of restaurants available in each price range.
Boxplot of Average Cost for Two by Price Range
Analyzes cost variations within each price range.
Scatterplot of Votes vs. Aggregate Rating
Examines the relationship between customer votes and ratings.


Step 4: Feature Engineering
Uses TF-IDF Vectorization to transform the Cuisines column into numerical format.

Step 5: Compute Similarity Matrix
Uses Cosine Similarity to measure the similarity between different restaurant cuisines.

Step 6: Recommendation System
How It Works:
Takes user inputs (Preferred Cuisine, Price Range).
Computes similarity scores for all restaurants based on cuisine.
Filters restaurants by the chosen price range.
Sorts recommendations based on similarity scores.
Returns the top-N recommendations.

Step 7: Testing the System
Example input:
python
Copy
Edit
user_cuisine = "Italian"
user_price_range = 2
recommendations = recommend_restaurants(user_cuisine, user_price_range)
print(recommendations)
Outputs the top 5 recommended restaurants that match the cuisine and price range.
