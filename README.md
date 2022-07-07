# BDCCLab_NetflixRS
BDCC Lab Project with Mark Acot (Term 4 SLT)

Executive Summary

Personalization is the name of the game. In an era where we are bombarded with so many choices, we want our choices to be curated to limit the guesswork and maximize our entertainment experience. In this study, we applied collaborative filtering using Spark's Machine Learning library MLlib on the Netflix dataset. The algorithm used for collaborative filtering was Alternating Least Squares (ALS) Matrix Factorization.

The model was run using the traditional machine learning pipeline comprising of separating a train and test set, cross validating the model, performing a grid search of the hyperparameters, evaluating the model using an error metric (RMSE) and inspecting the results. The model resulted to an RMSE of 0.8766, compared to the Netflix prize RMSE of 0.8995. These results can be improved if we can utilize the whole dataset. Due to system limitations, only 50% of the dataset was used.

The model was able to recommend movies for an individual user. Since the dataset did not have information on the genre of the movies, we generated it manually based on the title results. Most of the recommended movies corresponded with the user's highly rated genre, which was comedy.

This study was able to demonstrate the viability of performing collaborative filtering using ALS for large datasets. Recommendation for further studies include using the compelete dataset, comparing the performance with other recommender systems, and comparing the result of ALS to SVD using Surprise.
