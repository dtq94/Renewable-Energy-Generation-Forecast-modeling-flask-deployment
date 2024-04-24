# Renewable Energy Generation Forecast Modeling and Flask Deployment

## Objective

The objective of this project is to develop a predictive model for forecasting renewable energy generation based on time-series data. The model aims to predict various parameters related to renewable energy generation, including ActivePower, AmbientTemperature, BearingShaftTemperature, and others. Additionally, the project involves deploying the model using Flask to create a web application for making real-time predictions.

## Data

The dataset used in this project contains the following columns:
- ActivePower
- AmbientTemperature
- BearingShaftTemperature
- Blade1PitchAngle
- Blade2PitchAngle
- Blade3PitchAngle
- ControlBoxTemperature
- GearboxBearingTemperature
- GearboxOilTemperature
- GeneratorRPM
- GeneratorWinding1Temperature
- GeneratorWinding2Temperature
- HubTemperature
- MainBoxTemperature
- NacellePosition
- ReactivePower
- RotorRPM
- TurbineStatus
- WTG
- WindDirection
- WindSpeed

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Flask

## Project Components

1. Data Preprocessing: Cleaning and preparing the dataset for modeling.
2. Exploratory Data Analysis (EDA): Analyzing the dataset to gain insights and identify patterns.
3. Model Development: Building predictive models using machine learning algorithms such as XGBoost.
4. Model Evaluation: Assessing the performance of the trained models using appropriate evaluation metrics.
5. Flask Deployment: Creating a web application using Flask to deploy the predictive model for real-time predictions.
