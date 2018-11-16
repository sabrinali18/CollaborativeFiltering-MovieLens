# MovieLens-Recommendation

This project implements Item-Based and Matrix Factorization (MF) collaborative filtering (CF) algorithms using the MovieLens dataset.

### Objective
The main goal of building the CF models is to recommend movies to different users based on their ratings for movies they have seen before. Accuracy for each model is evaluated by Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE). Training error is caluclated by k-fold cross-validation. Item/User/Catalog coverages are defined and computed for each algorithm to evaluate the results of recommendation systems. Also, relationships between model size and accuracy/run-time are explored by changing the sample size included when fitting the model.
 
### Dataset
In this project, we used the MovieLens dataset from GroupLens Research. The dataset contains 100,000 ratings with 9,000 movies and 600 users. More information about MovieLens: https://grouplens.org/datasets/movielens/.

### Files
  - requirements.txt: Package requirements to run all the code
  - Item-Based_Collaborative_Filtering.ipynb: Implementation and Analysis of Item-Based CF model
  - Matrix_Factorization.ipynb: Implementation and Analysis of MF model
  - README.md: Introduction of the project
  
