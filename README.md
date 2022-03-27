# Movie Recommendation System

##### By: Catherine Ang


---

### Problem Statement
With more and more consumers accessing a greater volume of movie content than before - accelerated by the COVID-19 pandemic - it has become nearly a necessity for movie streaming services and platforms to incorporate personalisation in their movie recommendations to capture the consumers' attention.

In this project, we will build a Recommendation System to propose suitable movies to the end users, to boost their willingness to retain on the platform.

This project is inspired by [Analytics Vidhya](https://www.analyticsvidhya.com/blog/2018/06/comprehensive-guide-recommendation-engine-python/) and [rbr7's Github](https://github.com/rbr7/CF-movie_recommendation_system/blob/master/Movie_recommender_system.ipynb).

---

### About the Dataset
We will be working on the MovieLens dataset collected by the GroupLens Research Project at the University of Minnesota. The dataset consists of: 
- 100,000 ratings (1-5) from 943 users on 1,682 movies.
- Each user has rated at least 20 movies. 
- Demographic info of the users include: age, gender, occupation, zip
- Source: [MovieLens 100K Dataset](https://grouplens.org/datasets/movielens/100k/)

---

### Results
Comparing the Root Mean Squared Error (RMSE) scores, the Singular Value Decomposition model performs the best, as compared to both Collaborative Filtering models. 
- RMSE for User-User Collaborative Filtering: 3.5703075962160553
- RMSE for Item-Item Collaborative Filtering: 3.7528921332397456
- RMSE for Singular Value Decomposition: 2.8258075694458302

Top 5 movie recommendations have been generated for a selected user using the Singular Value Decomposition model. 

---

### Python Library Used
* Pandas
* Numpy
* Seaborn
* Matplotlib
* Sklearn
* Math
* SciPy