# CA05
# kNN based Movie Recommender Engine

## Brief Description:
Replicate of a recommender systems (sucha s movies on Netflix, videos in YouTube or articles on Medium) on a smaller scale, building the core of a movies recommender system. Using a given data set the goal is to find what are the 5 most similar movies to a movie query. Building a back-end recommendation engine.

## Code Explanation:
The code begins by setting up the data source and preparing the content. Next, it cleans the dataset by removing non-numerical columns and standardizing the remaining columns using StandardScaler(). Then, it constructs a recommender system using the k-nearest neighbors (kNN) model with k=5. Finally, it generates predictions for the 5 most similar movies to "The Post".

## Software:
* Python 3.x
* pandas
* numpy
* NearestNeighbors from sklearn.neighbors
* StandardScaler from sklearn.preprocessing

## Data Set:
The dataset is a small sub-set of the data extracted from the UCI Machine Learning Repository, IMDb's data set. The data set contains 30 movies, including data for each movie across seven genres and their IMDB ratings. The path for the data source: "https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv".

## Instructions:
Download the code file and run all in order. The Jupyter Notebook contains the entire code and logic for the decision tree classifier, as well as answers for the questions. Before running the program make sure you download the required package and import the needed libraries.

## Authors:
Riley Nickel, Taleen Barake, Lior Ben David
