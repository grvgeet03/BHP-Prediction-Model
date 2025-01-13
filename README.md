# Housing Price Prediction Model

This project demonstrates a machine learning model that predicts housing prices based on various parameters. It leverages a Kaggle dataset to train the model using the SciKit-Learn library. The project integrates data analysis, machine learning, and web development, providing a comprehensive solution for predicting house prices.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Dataset](#dataset)
4. [Data Preprocessing](#data-preprocessing)
5. [Model Development](#model-development)
6. [Backend Development](#backend-development)
7. [Frontend Development](#frontend-development)
8. [How to Run the Project](#how-to-run-the-project)

   
## Project Overview

This machine learning model predicts housing prices based on various parameters such as location, size, number of rooms, etc. It uses data preprocessing techniques to clean the data, followed by training a Linear Regression model to make accurate predictions. The model is deployed with a Flask backend, and the frontend is built with HTML, CSS, and JavaScript.

## Technologies Used

- **Machine Learning**: SciKit-Learn (Linear Regression, GridSearchCV, Cross-Validation)
- **Backend**: Flask
- **Frontend**: HTML, CSS, JavaScript
- **Data Processing**: Pandas
- **Model Serialization**: Pickle

## Dataset

The model is trained using a Kaggle dataset containing various features of houses such as size, location, number of rooms, etc., along with the target variable, which is the housing price.

## Data Preprocessing

1. **Data Cleaning**: 
   - Used Pandas to clean the dataset.
   - Removed any outliers to ensure the accuracy of the model.
   - Checked for missing values and handled them appropriately.

2. **Feature Engineering**:
   - Performed feature selection to identify the most relevant features for the model.
   - Normalized data to ensure uniformity across different features.

## Model Development

1. **Model Training**:
   - I used Linear Regression for training the model after performing GridSearchCV and Cross-Validation to determine the best performing algorithm.
   - Evaluated the performance of different classification techniques and chose Linear Regression based on the results.

2. **Model Serialization**:
   - After training the model, I serialized it using Pickle to save it and make it reusable in the future without retraining.

## Backend Development

1. **Flask**:
   - Flask is used to create a backend API that handles requests from the frontend and communicates with the trained model to predict housing prices.
   - The model is loaded from the Pickle file and predictions are returned in response to user inputs.

## Frontend Development

1. **HTML, CSS, JavaScript**:
   - The frontend of the application is built using HTML, CSS, and JavaScript to create an interactive UI.
   - Users can input various features of a house (like number of rooms, area, etc.), and the app returns the predicted house price.

## How to Run the Project

### Prerequisites:
1. Python 3.x
2. Required libraries (install via `requirements.txt`)
