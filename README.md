# Movie Recommender System
The main goal of this project is to recommend the 5 movies based on user interest.

## Table of Content
  * [Demo](#demo)
  * [Problem Statement](#problem-statement)
  * [Approach](#approach)
  * [Technologies Used](#technologies-used)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Detailed Project Reports](#detailed-project-reports)
  * [Bugs & Logs](#bugs--logs)
  * [Contributors](#contributors)

## Demo
Link: [https://moviesrecommenders.herokuapp.com/](https://moviesrecommenders.herokuapp.com/)

![Screenshot](Capture.PNG)


## Problem Statement
Dog Breed Identification
Determine the breed of a dog in an image
In today’s technology driven world, recommender systems are socially and economically critical for ensuring that individuals can make appropriate choices surrounding the content they engage with on a daily basis. One application where this is especially true surrounds movie content recommendations; where intelligent algorithms can help viewers find great titles from tens of thousands of options.

Providing an accurate and robust solution to this challenge has immense economic potential, with users of the system being exposed to content they would like to view or purchase - generating revenue and platform affinity.

## Approach
Data Exploration : I started exploring dataset using pandas,numpy,matplotlib and seaborn.

Feature Engineering : Removed missing values and created new features as per insights.

Pickle File : created pickle file as per need.

User Interface & deployment :  Created an UI with a form that take the necessary inputs from user and shows the 5 recommended movies.
                          After that I have deployed project on heroku.
## Technologies Used
 
   1. Python 
   3. Streamlit
   5. Sklearn(CountVectorizer, cosine_similarity)
   6. Pandas, Numpy 
 
## Dataset
   [Download here](https://www.kaggle.com/tmdb/tmdb-movie-metadata/download)

## Installation
Click here to install [python](https://www.python.org/downloads/). To install the required packages and libraries, run this pip command in the project directory after cloning the repository:
```bash
git clone https://github.com/hrishikeshkini/movie-recommender-system.git
pip install -r requirements.txt
```
If pip is not already installed, Follow this [link](https://pip.pypa.io/en/stable/installation/)

## Deployement on Heroku
Create a virtual app on Heroku Cloud. You can either connect your github profile or download cli to manually deploy this project.
Follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Bugs & Logs

1. If you find a bug, kindly open an issue and it will be addressed as early as possible. [Open](https://github.com/hrishikeshkini/movie-recommender-system/issues)
2. Under localhost, logging is performed for all the actions and its stored onto logs.txt file
3. When the app is deployed on heroku, logs can be viewed on  heroku dashboard or CLI.

## Contributors
  [Hrishikesh Kini](https://github.com/hrishikeshkini)
