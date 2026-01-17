# AAVAIL Time-Series Forecasting Capstone Project

## 1. Business Problem
AAVAIL requires a scalable system to forecast future revenue based on historical purchase behavior.
The forecasts are used to support business planning and decision-making.

## 2. Data Description
The dataset contains transactional and streaming activity data across multiple countries.
Data were aggregated and summarized by day to construct time-series features.

## 3. Modeling Approach
This project formulates the problem as a time-series regression task.
Historical revenue trends and seasonal patterns were used to train the model.
Classical regression techniques were applied after feature engineering.

## 4. Model Deployment
The trained model was deployed using a Flask API.
The API accepts a target date and country as input and returns a revenue prediction.
Docker was used to containerize the application for reproducibility.

## 5. Monitoring and Testing
Unit tests were implemented to validate data inputs and model behavior.
Logging was added to capture predictions, timestamps, and model versions.
Novelty detection techniques were considered to monitor performance drift.

## 6. Repository Structure
- notebooks/: exploratory analysis and modeling
- src/: data processing and model code
- app/: Flask application
- tests/: unit tests
- Dockerfile: container configuration

## 7. How to Run
1. Build the Docker image
2. Run the container
3. Send a prediction request to the Flask endpoint
