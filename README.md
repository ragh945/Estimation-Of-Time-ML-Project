# Estimation of Time for ML Project Using Streamlit
This repository contains a Streamlit application that estimates the time required for a machine learning project based on various input parameters. The model used for prediction is a pre-trained Linear Regression model.

link : https://estimation-project-4zxpwmfyw7fpdcdr9qgux6.streamlit.app/

## Features
- User-friendly interface to input parameters.
- Real-time prediction of project time based on inputs.
- Display of an image to enhance the visual appeal of the application.

## Prerequisites
- Python 3.x
- Streamlit
- Scikit-learn
- Pillow


## Enter the required input parameters:
- Start Latitude: The latitude where the project starts.
- Start Longitude: The longitude where the project starts.
- Destination Latitude: The latitude of the destination.
- Destination Longitude: The longitude of the destination.
- Distance: The distance to be covered.
- Density: The density of the data or tasks.
- Weather Condition: The weather condition (e.g., rainy, foggy, clear).
- Day: The day of the project.
- Hour: The hour of the project.
- 
  ## Submit the inputs to get the estimated time:
- Click on the Submit button.
- The estimated time will be displayed on the screen.

## Importing required Libraries
- import streamlit as st
- import pandas as pd
- import sklearn
- from sklearn.linear_model import LinearRegression
- import pickle
- from PIL import Image

## Description of libraries
- **streamlit** for creating the web application.
- **pandas** for data manipulation (if needed).
- **sklearn** for machine learning model.
- **pickle** for loading the pre-trained model.
- **PIL** for handling images.

# Deplyment of Estimation of Time Project using Streamlit 
![image](https://github.com/user-attachments/assets/af0decff-fe60-4386-907b-0e1a870283a3)
