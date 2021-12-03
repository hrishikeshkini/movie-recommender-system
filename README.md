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
![Screenshot](Capture2.PNG)



## Problem Statement
Dog Breed Identification
Determine the breed of a dog in an image
Who's a good dog? Who likes ear scratches? Well, it seems those fancy deep neural networks don't have all the answers. However, maybe they can answer that ubiquitous question we all ask when meeting a four-legged stranger: what kind of good pup is that?

You are provided a strictly canine subset of ImageNet in order to practice fine-grained image categorization. How well you can tell your Norfolk Terriers from your Norwich Terriers? With 120 breeds of dogs and a limited number training images per class, you might find the problem more, err, ruff than you anticipated.

## Approach
Data visualization : Ploted graphs to get insights about dependend and independed variables.

Model Building & Testing : Tried many deep learning combinations and checked the base accuracy to find the best fit.

Save model : Selected model as per best accuracy and saved model using keras.

User Interface & deployment :  Created an UI with a form that takes image inputs from user and shows the output.
                          After that I have deployed project on heroku.
## Technologies Used
 
   1. Python 
   2. Tensorflow
   3. Streamlit
   4. Keras
   5. Sklearn
   6. Pandas, Numpy 
   7. Matplotlib
   8. Open-cv

## Installation
Click here to install [python](https://www.python.org/downloads/). To install the required packages and libraries, run this pip command in the project directory after cloning the repository:
```bash
git clone https://github.com/hrishikeshkini/Dog-Breed-Prediction.git
pip install -r requirements.txt
```
If pip is not already installed, Follow this [link](https://pip.pypa.io/en/stable/installation/)

## Deployement on Heroku
Create a virtual app on Heroku Cloud. You can either connect your github profile or download cli to manually deploy this project.
Follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Bugs & Logs

1. If you find a bug, kindly open an issue and it will be addressed as early as possible. [Open](https://github.com/hrishikeshkini/Dog-Breed-Prediction/issues)
2. Under localhost, logging is performed for all the actions and its stored onto logs.txt file
3. When the app is deployed on heroku, logs can be viewed on  heroku dashboard or CLI.

## Contributors
  [Hrishikesh Kini](https://github.com/hrishikeshkini)
