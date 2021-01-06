# Movie-Recommender-System

● Ziaul Kadri

● Ujjwal Gupta

● Supriya kumari Gupta

● Himanshi kumari Gupta

Content Based Recommender System Working
Content Based Recommender System recommends items similar to the items user likes. How does it decide which item is most similar to the item user likes. Here we use the similarity scores.
Content based recommender systems recommends similar items used by the user in the past.

For example, Netflix recommends us the similar movies to the movie we recently watched.

Similarly, Youtube also recommends us similar videos to the videos in our watch history.

● Similarity Score :It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items.

Here we’ll use cosine similarity between text details of items. In the example below it is shown how to get cosine similarity:

![cosine](https://user-images.githubusercontent.com/57566639/103796867-c1eb1b00-506d-11eb-8fb4-20e061d8b27d.jpg)

This is a hollywood movie recommender system built with Python. I used IMDB 5000 Movie Dataset to built this.
Link to dataset :- https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset

I used Flask web framework in built in Python to put in on web.

# Files Brief
*In the preprocessing.ipynb file the Data Preprocessing part has been done. 

*In the create.py file I created two files for future uses one data.csv and other a numpy matrix.

*The application is run from the main.py file.
