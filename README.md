
# Movie Lens

<img width="623" alt="Screenshot 2024-06-17 at 9 49 22 AM" src="https://github.com/Suhana2424/MovieRecommadationSys/assets/165405660/a0e95075-59b7-442f-889e-e2266ee9278b">

Recommendation system is an algorithmic tool that uses predictive modelling to suggest relevant items to user based on their past behavior and preferences. These systems improve customer experience, drive user engagement, and maximize revenue opportunities by personalizing the offerings. Used extensively in e-commerece, streaming services, and other digital platforms, recommendation systems form a crucial part of data-driven business strategies.

- Collaborative 
- Content-based
- Hybrid

# Collaborative Filtering Algorithm

The Collaborative filtering Algorithm calculates item-item similarity scores based on user-item interaction data. It measures the similarity between items by analyzing the patterns of user interactions. The algorithm then generates recommendation by selecting items that are similar to the ones a user has already interacted with. 

<img width="505" alt="Screenshot 2024-06-17 at 11 01 12 AM" src="https://github.com/Suhana2424/MovieRecommadationSys/assets/165405660/60bf421e-fae1-46f2-bfee-db0aa5b888bb">


# Item-Item Similarity

Item-Item similarity, also known as Item-Based Collaborative Filtering, is a popular technique used in recommendation systems. It focuses on finding similarities between items based on user interactions and preferences. The primary idea is to recommend items to a user that are similar to the ones they have shown interest in or interacted with before.

The process of Item-Item similarity can be summarized as follows:

- Create an item-item similarity matrix: Calculate the similarity between each pair of items using a similarity metric such as cosine similarity or Pearson correlation.
- Identify similar items for a given item: When a user expresses interest in a specific item, retrieve its most similar items from the similarity matrix. 
- Generate recommendations: Recommend these similar items to the user, as they are likely to align with the user's preferences.
- Examples : Checkout and Product pages recommendation

# Calculation 


# User-Item Similarity

User-Item Similarity, also known as User-Based Collaborative Filtering, is another widely used technique in recommendation systems. Instead of focusing on item similarities, it emphasizes identifying similar users based on their past interactions and preferences. The idea is to recommend items to a user based on items that similar users have liked or interacted with in the past. 
The process of User-Item Similarity can be summarized as follows:

- Create a user-item interaction matrix: Build a matrix where rows represent users, columns represent items, and the entries indicate user-item interactions(e.g., ratings, clicks, purchase).
- Calculate user-user similarity: Use a Similarity metric like cosine similarity or Pearson correlation to finds the similarity between each pair of users based on their interactions.
- Identify similar users: For a target user, Identify the most similar users from the similarity matrix.
- Generate recommendations: recommend items to the target user based on the items preferred or interacted with by the most similar users.
- Examples: Home page recommendation.

# Cold start problem 

The Cold Start Problem is a common challenge faced by recommendation systems when dealing with new users or new items that have limited or no historical interactions data. It refers to the difficulty of generating accurate and relevant recommendations for users or items with insufficient data available for analysis.

# Dataset

    https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset

Consists of:

- 100,000 ratings (1-5) from 943 users on 1682 movies.
- Each user has rated at least 20 movies.

# Resources 

    http://files.grouplens.org/papers/www10_sarwar.pdf
## Live Demo link

    https://item-item-similaritysearch-suhana2424.streamlit.app/
