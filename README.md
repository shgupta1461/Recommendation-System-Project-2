# Recommendation-System-Project-2
Course Project 2

## Beer Recommendation System using Collaborative Filtering Technique
**Introduction**
This project implements a recommendation system based on collaborative filtering techniques, specifically focusing on matrix factorization. Collaborative filtering is a method commonly used in recommendation systems to predict a user's interests by collecting preferences from many users. Matrix factorization techniques aim to decompose the user-item interaction matrix into latent factors representing user preferences and item characteristics.

**Approach**
The recommendation system employs the following steps:

1. **Data Analysis:** Preprocess the user-item interaction data to construct the user-item matrix.
2. **Matrix Factorization:** Apply matrix factorization technique of Least Squares (LS), or Stochastic Gradient Descent (SGD) to factorize the user-beer matrix.
3. **Model Training:** Train the matrix factorization model on the preprocessed data to learn the weights of latent factors.
4. **Prediction:** Generate recommendations for users based on the learned latent factors.
5. **Evaluation:** Evaluate the performance of the recommendation system using appropriate metrics such as precision, recall, F1 score and mean squared error (MSE).

- ACCURACY OBTAINED: 73.1%
- DATASET: beeradvocate.csv (https://cseweb.ucsd.edu/~jmcauley/datasets.html#multi_aspect)

**Requirements**
1. Python (>=3.6)
2. NumPy
3. pandas
4. scikit-learn
5. matplotlib
6. seaborn

**References**
1. Practical Recommendation System by Oreilly book
2. Recommendation System textbook by Charu Aggarwal
3. Recommender Systems Handbook.
4. Online Articles 
5. Learning attitudes and attributes from multi-aspect reviews
Julian McAuley, Jure Leskovec, Dan Jurafsky
International Conference on Data Mining (ICDM), 2012
6. From amateurs to connoisseurs: modeling the evolution of user expertise through online reviews
Julian McAuley, Jure Leskovec
WWW, 2013

**Contributors**
1. Shashwat Parikh
2. Shubham Gupta
3. Kavisha Madani
4. Mayan Bhut
