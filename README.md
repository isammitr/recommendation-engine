# Building a Recommendation Engine
Analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like

## Tasks Accomplished:

### 1. Exploratory Data Analysis

**My Findings:**

- 50% of individuals have  **3**  or fewer interactions.
- The **total** number of user-article interactions in the dataset is  **45993**.
- The **maximum** number of user-article interactions by any 1 user is  **364**.
- The **most viewed** article in the dataset was viewed **937**  times.
- The article_id of the most viewed article is  1429.0.
- The number of **unique article**s that have at least 1 rating **714**.
- The number of **unique users** in the dataset is  **5148**.
- The number of **unique articles** on the IBM platform is **1051**.

### 2. Rank Based Recommendations

**The Top 10 articles based on popularity to recommend to new users (for a Cold-Start Problem) are:**

1. 'use deep learning for image classification', 
2. 'insights from new york car accident reports', 
3. 'visualize car data with brunel',
4. 'use xgboost, scikit-learn & ibm watson machine learning apis', 
5. 'predicting churn with the spss random tree algorithm', 
6. 'healthcare python streaming application demo', 
7. 'finding optimal locations of new store using decision optimization', 
8. 'apache spark lab, part 1: basic concepts', 
9. 'analyze energy consumption in buildings', 
10. 'gosales transactions for logistic regression model'


### 3. User-User Based Collaborative Filtering

**The top 10 recommendations for user 20 are the following article names (These recommendations would be more personalized to each user):**

1. 'deep learning from scratch i: computational graphs'
2. 'using machine learning to predict baseball injuries'
3. 'gosales transactions for logistic regression model', 
4. 'airbnb data for analytics: venice listings'
5. 'analyze accident reports on amazon emr spark'
6. 'pixieapp for outlier detection'
7. 'build a naive-bayes model with wml & dsx'
8. 'uci: white wine quality'
9. 'deploy your python model as a restful api'
10. 'visualize the 1854 london cholera outbreak'

### 4. Matrix Factorization

Finally, a machine learning approach is completed to build recommendations. Using the user-item interactions, a matrix decomposition has been built out. Using this decomposition, we get an idea of how well the model can predict new articles an individual might interact with. Lastly, methods have been discussed which could be used moving forward, and how you might test how well your recommendations are working for engaging users.

### `TODO:`

Build a Flask app to host this recommender system.
