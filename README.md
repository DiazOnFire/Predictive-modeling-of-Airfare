
# Predictive Modeling of Airfare using Machine Learning

## Overview

Flight fare prediction is a classical problem of time series forecasting that identifies trends in past observations to forecast future prices. This project leverages these trends to predict flight fares based on a given set of travel details. Popular flight booking websites, including Google Flights, provide insights such as:

- Current fare status: high, low, or fair
- Past fare trends and upcoming future trends
- Guidance on the optimal time to book a flight ticket

## Project Description

In this project, we have developed a Python-based Flight Fare Prediction App using Flask. The application returns fare predictions for a specified set of travel details, including:

- Departure date
- Arrival date
- Departure city
- Arrival city
- Number of stoppages
- Airline carrier

## Key Features

- **Extensive Preprocessing**: Handling missing values, encoding categorical variables, scaling features, and more to ensure the dataset is clean and suitable for modeling.
- **Feature Selection**: Identifying the most relevant features that contribute to fare prediction to improve model performance and efficiency.
- **Model Building**: Utilizing machine learning algorithms to build a predictive model that can accurately forecast flight fares.
- **Flask Web Application**: Creating a user-friendly web interface using Flask to allow users to input travel details and receive fare predictions.

## Usage
1. Enter the travel details such as departure date, arrival date, departure city, arrival city, number of stoppages, and airline carrier.
2. Click on the 'Predict Fare' button to get the predicted fare for the given travel details.
