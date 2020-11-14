

# Flight-Fare-Prediction
This is a flask app which predicts fare for different flights across India. The guidance for this project was taken from Krish Naik's youtube channel https://www.youtube.com/watch?v=y4EMEpEnElQ.

## Overview:
This is one of the best projects that I have come across. Unfortunately, the dataset is only specific to India and can't be used anywhere else. I am working on building a similar dataset for Pakistan. Hope it gets completed soon. This app uses machine learning algrithm in the backend to predict fare for a flight givn different inputs. The step by step guide for the project an be taken here from this link https://www.youtube.com/watch?v=y4EMEpEnElQ.

## Dataset
The dataset for this project can be obtained from kaggle here at this link https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh/.

## Code and Dependencies:
The code was written using jupyter notebook in Python 3.8. The other tools that were used were scikit-learn, flask, numpy, pandas, gunicornetc.

## Model:
The random forest regressor was used to train the model. The model was saved using pickel so that it could be used later in the flask app. The model gave an accuracy of around 81% which is actually quite good. 

## Deployment:
I deployed the model on heroky but later on it started giving a Unicode error. Till, I solve the problem I am going to be putting it off for the heroku platform. 
