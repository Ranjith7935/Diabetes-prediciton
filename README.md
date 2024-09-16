### Diabetes-prediciton

### software and Tools Resquiirements

1. [Github](https://github.com)
2. [Heroku](https://heroku.com)
3. [VS code](https://code.visualstudio.com/)
4. [Git Cli](https://git-scm.com/)
# Diabetes Prediction Flask App

## Overview

This project provides a web application for predicting diabetes using a trained regression model. The app is built with Flask and uses a pre-trained model and scaler, both of which are loaded using `pickle`. The application supports two types of predictions:

1. **API Endpoint**: Provides predictions via a JSON API.
2. **Web Interface**: Allows users to input data through a web form and view predictions directly on the web page.

## Features

- **Web Interface**: User-friendly HTML form for input and prediction display.
- **API Endpoint**: Allows external applications to send data and receive predictions in JSON format.
- **Model**: Trained regression model for diabetes prediction.
- **Scaler**: StandardScaler used for feature scaling.

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**

   ```bash
   
   
   
   cd Diabetes-prediction

2.  **Create new environment**
    ```bash
    python -m venv venv
    .\venv\Scripts\activate

3.  **Install Dependencies**
     
5.  **Prepare the Model and Scaler**
6.  **Run the Application**
