# Deploy_a_Sentiment_Analysis_Model
This repository contains all related files of the Udacity Machine Learning Engineer Nanodegree, Deploying a Sentiment Analysis Model project.

The model contains
1. A sentiment recurrent neural network model deployed on AWS
2. A web application that allows enter reviews of movies

The design of this model contains: a deployed sentimental analysis model, lambda function, API and a webpage. This simple web app which interacts with the sentimental analysis model on movie reviews.

## Installation
- sagemaker==1.72.0
- python3
- glob
- sklearn
- nltk
- pickle
- numpy
- pandas
- sagemaker
- torch

Other required libraries for deployed model includes in the [train/requirements.txt](https://github.com/Mendy5/Udacity_Deploy_a_Sentiment_Analysis_Model/blob/main/train/requirements.txt) file

## Data Source
[IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/)

## Project Motivation
This simple web app which interacts with the sentimental analysis model on movie reviews.

## Results
The final product is a webpage. The users can enter a review of a movie and submit it. The sentimental results will show if it is a positive or negative review on the webpage.

# Licensing, Authors, Acknowledgements
Must give credit to Andrew Maas for the data.
