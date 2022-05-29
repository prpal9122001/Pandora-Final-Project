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

# Agile development Methodology

* I divided the one-month program into four sprints. Each sprint consisted of one week period.
* I categorized my sprints into four sections - exploration, basic working model, features creation, adapt phase.
* We were given a problem statement in which we had to make a web app that could connect two users over a video call.
* After researching, I found that most of the recommendation apps use Cosine similarity.
* In the second week, I created an basic idea of what kinda work I want my app to do.
* In the third week, I scaled it and after some reconsiderations I worked on the challenge and added custom functionalities. 
* In the fourth week, ie. Adapt phase, we had to create a web app that could give me accurate answers from database without disrupting the flow.

Trying my best to complete the given challenge and provide solution to the problem statement chosen by me.

## Recommendation system and algorithm explained

* Nearest Neighbours:
  
  I have used nearest neighbours algorithm to find the most related list of movies to a movie name. This algorithm takes argument named **'metric'**.I have assigned this argument to **'cosine'**. If two movies are highly related then the cos value will be equal to 1 as angle between them will be 0 degree. If movies are not related then angle between them will be 90 degree and value will equal to 0 (cos90=0).
  
![](Images/cosine.png)

**READ MORE AT = Algorithm_and_Recommender_sys.ipynb in reposit**

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

## Requirement
* Sign In to Google Colab and Google Drive
* Upload Logo,Movie_list().pkl and similarity().pkl on google drive 
* You can get Movie_list().pkl and similarity().pkl by running end cell from Pandora Movie Recommendation notebook
* In case of error in streamlit run try to rerun the cell

## Features and Interfaces

![Screen Shot 2022-05-29 at 4 28 55 AM](https://user-images.githubusercontent.com/72788936/170849426-fc5e285f-ae48-44b6-b611-018a9183532e.png)

![Screen Shot 2022-05-29 at 4 28 36 AM](https://user-images.githubusercontent.com/72788936/170849424-13aead78-65d6-44c4-97f7-2216e8a99f5d.png)

![Screen Shot 2022-05-29 at 4 28 55 AM](https://user-images.githubusercontent.com/72788936/170849496-2c7fea94-d35f-491a-89ae-55ff7525885f.png)

![Screen Shot 2022-05-29 at 4 29 19 AM](https://user-images.githubusercontent.com/72788936/170849414-203cc022-3e60-4dbe-8c71-e46b8deb6614.png)

## Connect with me
Drop by and say hello!

[<img height="30" src="https://img.shields.io/badge/linkedin-0077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />][LinkedIn]

[linkedIn]: https://www.linkedin.com/in/preeti-pal-1109






