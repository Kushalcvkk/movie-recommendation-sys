app.py:-
       This file contains the fornt end code done using streamlit package in python , and the data model of movies given by the "movie-recommendation-sys.ipynb".
movie-recommendation-sys.ipynb:- 
       This contains the model created using the datasets "tmdb_5000_credits" and "tmdb_5000_movies".
       using data_precprocessing I have merged these two files into one data_frame
       Then I have converted the data into vectors on 2D plane and based on the angles btw the vector points I have determined the closest points(movies),all the similarities among movies is made into a 4806X4806 matrix.
       Based on the sorted  matrix I pulled of the top 5 similar movies searched by user.
All other files are part of deployement.       
       
       
