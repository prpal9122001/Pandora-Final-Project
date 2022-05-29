# PANDORA - Movie Recommendation Webapp
## Submission for Microsoft Engage 2022 🌟
<img src="Logo.png" alt="drawing" width="300"/>

Who has never wanted to find a great movie to see in a weekend or holiday? Who has never started to watch a movie thinking it would be good but it was terrible? Pandora can help you to stop to lose your time trying to find a good one.

## About

PANDORA is a Movie Recommendation content based App using cosine similarity with fast result to solve your problem of finding what movie to watch today with friends,family & colleagues.

Developed during my menteeship at [Microsoft Engage 2022](https://acehacker.com/microsoft/engage2022/)

An open movie recommendation API that has been built using Google Colab and deployed on Streamlit localtunnel.



It implements the following features:

* It focuses on the information of movies, and helps people to find a movie by different key words then recommend some similar movies to users
* Just enter one movie name then it will recommend 5 movies at the same time.

## Platform Used

* **Google Cloud** - This whole app is based on Google Cloud reason being that I wanted to build an app  that is easy to test and deploy as well as function that does not require many installations as well as doesn't use space on my device. Using its free and powerful computation service helps us in build up and deployment on cloud platform.The advantage of running a web app on Colab is that the app is not limited by the limited computation of free tier accounts, you can even have a runtime with GPU.However, the major drawback of it is the URL is only temporary, once the Colab is disconnected, the URL will be disabled. So you can   only share the link for a short period (<12hrs). But I think it is still a good approach to quickly deploy, test, and share a web app prototype.


* **Streamlit** - It is a powerful tool to create simple web applications in Python. It is very convenient for people without web development background.

## Dataset used
I have used TMDB 5000 movie dataset.              
This dataset containd two csv files:
  1. tmdb_5000_credits.csv
  2. tmdb_5000_movies.csv

Link to dataset: https://www.kaggle.com/tmdb/tmdb-movie-metadata

## Libraries used
* Pandas
* Numpy
* CountVectorizer
* cosine_similarity
* Rake_nltk
* Sklearn
* Streamlit

# Recommendation system and algorithm explained

Link = "Algorithm_and_Recommender_sys.ipynb"





