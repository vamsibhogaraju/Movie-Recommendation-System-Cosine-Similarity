# Movie-Recommender-System using Cosine Similarity


## Content Based Recommender System with Heroku Deployment
One popular technique of recommendation/recommender systems is content-based filtering. Content here refers to the content or attributes of the movies you like. So, the idea in content-based filtering is to tag products using certain keywords, understand what the user likes, look up those keywords in the database and recommend different movies with the same attributes.

## Cosine Similarity
* Cosine Similarity from Sklearn is used, as the metric to compute the similarity between two movies.
* Cosine similarity is a metric used to measure how similar two items are. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space.
* The output value ranges from 0–1.0 means no similarity, where as 1 means that both the items are 100% similar.

![alt](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.BuCMhjf0AAMZ0FE4mT-A_QHaFt%26pid%3DApi&f=1 "Cosine Similarity")

## Libraries Used
**For Model Building**
* Numpy
* Pandas
* Sklearn

**For Front-End**
* Streamlit

## Deployment
To Deploy the model in heroku run the comands in Terminal:

```
$ heroku login
$ heroku git:clone -a "your app name in heroku" 
$ cd "Path"
$ git config core.autocrlf true
$ git add .
$ git commit -am "make it better"
$ git push heroku master
$ heroku ps:scale web=1

```






* ***Dataset link*** : https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
* ***Streamlit*** : https://docs.streamlit.io/library/cheatsheet
* ***Model*** : https://movierecommendersystem-vamsi.herokuapp.com/
