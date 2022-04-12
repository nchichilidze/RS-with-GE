# Building a Recommender System with Grammatical Evolution

🌷 This is my final year project for the B.Sc. degree in Computer Systems at the University of Limerick.

The project focused on building/optimising a recommender system with the help of Grammatical Evolution. For the final result, 
I managed to show that GE is able to generate a lower RMSE score (mean RMSE: 0.777) compared to the SVD Collaborative Filtering
algorithm when given 19 movie-related features including (a content-based filtering rating, a collaborative filtering prediction, etc). 

This recommender system can be considered a hybrid recommender system as it uses both the collaborative and content-based filtering in
addition to dozens of other features.

🌷 The final product is located in the \submission directory 

* rs-with-ge.ipynb - notebook with data preprocessing, feature engineering and a singular 500 generation GE run resulting in an improved RMSE 
* quantitative_experiments.ipynb - notebook with 15 250 generation GE runs resulting in a mean\avg RMSE improvement compared to the SVD CF algorithm
* preprocessed_movielens_data - data from movielens, cleaned and preprocessed for feature engineering 

🌷 The data used for the project were: 

* MovieLens by GroupLens
* IMDB Datasets by IMDB 
* Movie Dataset by TMDB 

🌷 The packages/libraries used for the project were: 

* GRAPE
* Numpy
* Pandas
* RS Datasets
* SimpleTMDB
* Surprise
* Sklearn
