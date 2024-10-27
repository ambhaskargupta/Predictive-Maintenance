# Predictive-Maintenance
### Predictive Maintenance Model with LSTM for Machine Failure Prediction

This project leverages deep learning with Long Short-Term Memory (LSTM) networks to predict the likelihood of machine failure within the next 30 days, enabling proactive maintenance. By analyzing 30-day historical sequences of device metrics, this model identifies patterns and provides a probability score for failure, helping to minimize unplanned downtime and improve operational efficiency.

### Features

$ Time-Series Data Processing: Historical metrics are normalized and sequenced for each device over 30-day windows.

LSTM Architecture: A multi-layered LSTM model captures sequential dependencies in time-series data to predict future failures.

Failure Probability Prediction: Given a specific device model, the model outputs the probability of failure within the next 30 days.

Proactive Maintenance: Predictions support maintenance scheduling, reducing operational costs and maximizing equipment lifespan.


### Usage

Data Preprocessing: Prepares and normalizes the dataset by creating 30-day sequences for each device.

Model Training: Trains the LSTM model on historical data with labeled sequences.

Prediction: For a specified device, the model predicts the probability of failure based on the last 30-day metrics.

### Results

This model can effectively predict the probability of failure based on historical data, allowing for data-driven maintenance decisions.




