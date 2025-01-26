Overview of the Project 
This project focuses on predicting rainfall in Austin, TX area using multiple machine learning and deep learning models, including:

Linear Regression
Support Vector Machine (SVM) Regressor
Random Forest Regressor
Artificial Neural Networks (ANN)
CatBoost Regressor
The models are trained on real-world weather data to predict rainfall levels based on environmental factors.

Dataset
The dataset is a weather dataset containing the following columns:
created_at: Timestamp of data recording
Rain Drop Value: Target variable (amount of rainfall)
Other meteorological features (e.g., temperature, humidity, pressure)

Project Workflow
Data Preprocessing
Convert timestamps to Year and Month features
Standardize feature values using StandardScaler
Split data into training and testing sets
Model Training & Evaluation

Train different regression models
Evaluate performance using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score
Model Comparison

Compare models based on performance metrics
Visualize errors and R² scores using boxplots
Prediction on New Data

Use a trained CatBoost model to predict rainfall for given environmental conditions


Results & Insights from the project 
Random Forest and ANN models performed the best, showing the highest R² scores.
Linear Regression had the highest error rates due to its simplicity.
CatBoost showed promising results for real-time predictions.
