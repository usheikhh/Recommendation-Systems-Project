# **Amazon Product Recommendation System**


Welcome to the project on Recommendation Systems. We will work with the Amazon product reviews dataset for this project. The dataset contains ratings of different electronic products. It does not include information about the products or reviews to avoid bias while building the model. 

--------------
## **Context:**
--------------

Today, information is growing exponentially with volume, velocity and variety throughout the globe. This has lead to information overload, and too many choices for the consumer of any business. It represents a real dilemma for these consumers and they often turn to denial. Recommender Systems are one of the best tools that help recommending products to consumers while they are browsing online. Providing personalized recommendations which is most relevant for the user is what's most likely to keep them engaged and help business. 

E-commerce websites like Amazon, Walmart, Target and Etsy use different recommendation models to provide personalized suggestions to different users. These companies spend millions of dollars to come up with algorithmic techniques that can provide personalized recommendations to their users.

Amazon, for example, is well-known for its accurate selection of recommendations in its online site. Amazon's recommendation system is capable of intelligently analyzing and predicting customers' shopping preferences in order to offer them a list of recommended products. Amazon's recommendation algorithm is therefore a key element in using AI to improve the personalization of its website. For example, one of the baseline recommendation models that Amazon uses is item-to-item collaborative filtering, which scales to massive data sets and produces high-quality recommendations in real-time.

----------------
## **Objective:**
----------------

You are a Data Science Manager at Amazon, and have been given the task of building a recommendation system to recommend products to customers based on their previous ratings for other products. You have a collection of labeled data of Amazon reviews of products. The goal is to extract meaningful insights from the data and build a recommendation system that helps in recommending products to online consumers.

-----------------------------
## **Dataset:** 
-----------------------------

The Amazon dataset contains the following attributes:

- **userId:** Every user identified with a unique id
- **productId:** Every product identified with a unique id
- **Rating:** The rating of the corresponding product by the corresponding user
- **timestamp:** Time of the rating. We **will not use this column** to solve the current problem


## Content
* Exploratory Data Analysis
    * Checking the number of rows and columns and providing observations 
    * Checking data types 
    * Checking for missing value in the data
    * Summary statistics of 'rating' variable and provide observations 
    * Creating the bar plot to check the 'rating' distribution
    * Checking the number of unique USERS and PRODUCTS in the data

* Model Building - Rank Based Recommendation System
    * Recommending top 5 products with 50 minimum interactions based on popularity 
    * Recommending top 5 products with 100 minimum interactions based on popularity

* Model Building - User-User Similarity-based Recommendation System
    * Initializing a baseline user-user similarity based recommendation system 
    * Fitting the model on the training data 
    * Using a function to calculate the metrics on the test data

* Improving Model Performance - User-User Similarity-based (Optimized) Recommendation System
    * Performing hyperparameter tuning for the user-user similarity-based model 
    * Building the optimized model by using tuned values of the hyperparameters
    * Predicting the rating for a user using the optimized model

* Model Building - Item-Item Similarity-based Recommendation System
    * Initializing a baseline user-user similarity based recommendation system 
    * Fitting the model on the training data 
    * Using a function to calculate the metrics on the test data

* Improving Model Performance - Item-Item Similarity-based (Optimized) Recommendation System
    * Performing hyperparameter tuning for the user-user similarity-based model 
    * Building the optimized model by using tuned values of the hyperparameters
    * Predicting the rating for a user using the optimized model

* Model Building - Matrix Factorization based Recommendation System
    * Initializing a baseline user-user similarity based recommendation system 
    * Fitting the model on the training data 
    * Using a function to calculate the metrics on the test data

* Improving Model Performance - Matrix Factorisation based (Optimized) Recommendation System
    * Performing hyperparameter tuning for the user-user similarity-based model 
    * Building the optimized model by using tuned values of the hyperparameters
    * Predicting the rating for a user using the optimized model

* Conclusion & Recommendations
    * Comparing different models' performance and choosing the final model with reasoning 
    * Providing recommendations that can be acted upon to improve the business outcome


# Skills
* Data Preprocessing:
    * Cleaning and preparing data specifically for building recommendation models.
    * Handling missing values, encoding, and transforming features for model input.*

* Collaborative Filtering:
    * Implementing user-based or item-based collaborative filtering techniques.
    * Using similarity measures such as cosine similarity, Pearson correlation.

* Matrix Factorization:
    * Implementing algorithms like Singular Value Decomposition (SVD) for latent factor models.
    * Using matrix factorization to decompose user-item interaction matrices.

* Content-Based Filtering:
    * Extracting features from user or item profiles to recommend similar items.
    * Vectorizing textual or categorical data (e.g., using TF-IDF or count vectors).

* Evaluation Metrics:
    * Calculating accuracy metrics such as RMSE (Root Mean Squared Error), precision, recall, and F1-score.
    * Implementing cross-validation or other evaluation techniques to assess model performance.

* Data Visualization:
    * Visualizing recommendation outcomes, user-item interactions, or the effects of different algorithms.
    * Using libraries like matplotlib or seaborn for plotting.

* Model-Based Approaches:
    * Using machine learning models such as matrix factorization models (e.g., SVD) for predictions.
    * Tuning hyperparameters to improve recommendation quality.

* Exploratory Data Analysis (EDA):
    * Performing EDA to understand the characteristics of users and items, such as ratings distribution and user behavior.

* Prediction and Ranking:
    * Building systems that generate personalized rankings or lists of recommended items based on user preferences or historical data.