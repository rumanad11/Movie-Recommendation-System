# Movie Recommendation System
Domain: Machine Learning
Project Type: Collaborative Filtering-based Recommender System

# Business Objective
In today's digital landscape, entertainment platforms like Netflix, Amazon Prime, and YouTube host vast catalogs of content. With millions of options available, users often face decision fatigue when choosing what to watch. This is where Recommendation Systems play a critical role by narrowing down choices and offering personalized suggestions.
The primary business goals of this project are:
-To build a Collaborative Filtering-based Movie Recommendation System.
-To predict user ratings for movies they haven’t yet watched.
-To minimize prediction error using evaluation metrics like RMSE (Root Mean Square Error) and MAPE (Mean Absolute Percentage Error).

# Data Collection
The dataset used for this project is the MovieLens 20M dataset, provided by GroupLens Research.
Dataset link: https://grouplens.org/datasets/movielens/20m/

 Key Details:
-Contains 20 million+ ratings and 465k+ tag applications for 27,278 movies.
-Data collected from 138,493 users (each having rated at least 20 movies) between 1995 and 2015.
-For this project, we utilized the ratings.csv and movies.csv files.

# Modeling Approach
The following steps outline the modeling and analytical pipeline:
# 1. Data Loading & Exploration
-Imported and cleaned data from ratings.csv and movies.csv.
-Performed exploratory data analysis to understand user and movie interactions.
# 2. Similarity Matrix Construction
-Built User-Item Matrix, User-User Similarity Matrix, and Item-Item Similarity Matrix for collaborative filtering.
# 3. Model Building
-Applied Collaborative Filtering algorithms to generate movie recommendations.
-Used matrix factorization techniques to predict unseen ratings.
-Trained and evaluated models using supervised learning approaches to refine predictions.
# 4. Evaluation Metrics
-Performance measured using RMSE and MAPE to quantify prediction accuracy.

# Results
- Movie-Movie Similarity Results: Provided content-based recommendations based on item similarity.
- User-User Similarity Results: Generated personalized recommendations by identifying similar users.
- Feature Importance: Assessed key variables contributing to rating prediction.
- Model Comparison: Evaluated multiple ML models to find the best performing approach for rating prediction.
- Sample Recommendations: Displayed recommended movies for a user based on collaborative filtering output.

# Conclusion
This project demonstrates how Collaborative Filtering and matrix factorization can be used to build an effective movie recommendation engine. Key takeaways include:
-Understanding the foundations and impact of recommendation systems.
-Constructing and analyzing similarity matrices to drive predictions.
-Implementing models that dynamically predict unseen ratings based on user behavior.
-Evaluating model performance using error metrics like RMSE and MAPE.
While the current system provides valuable recommendations, there is significant scope for enhancement. Future improvements could include:
-Incorporating Deep Learning models (e.g., Neural Collaborative Filtering)
-Integrating content-based features such as genres and tags
-Exploring hybrid recommender systems for better personalization

