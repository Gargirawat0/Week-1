# Week-1
Build a regression model that forecasts future EV adoption demand based on historical trends in EV growth, types of vehicles, and regional data.

# Week-2
This project focuses on forecasting the adoption of Electric Vehicles (EVs) using historical data on vehicle registrations. The goal is to build a regression model that predicts future EV adoption based on trends in EV growth, vehicle types, and regional data. The dataset includes information on Battery Electric Vehicles (BEVs), Plug-In Hybrid Electric Vehicles (PHEVs), and Non-Electric Vehicles, categorized by county and month.

Dataset
The dataset used in this project is sourced from Kaggle and contains the following key features:

Date: Monthly registration counts.

County: Geographic region of vehicle registration.

State: Geographic region associated with the record.

Vehicle Primary Use: Primary intended use of the vehicle (Passenger or Truck).

Battery Electric Vehicles (BEVs): Count of vehicles powered solely by an electric battery.

Plug-In Hybrid Electric Vehicles (PHEVs): Count of vehicles partially powered by an electric battery.

Electric Vehicle (EV) Total: Sum of BEVs and PHEVs.

Non-Electric Vehicle Total: Count of non-electric vehicles.

Total Vehicles: All powered vehicles registered in the county.

Percent Electric Vehicles: Percentage of electric vehicles relative to total vehicles.

Project Structure
The project is organized into the following steps:

Data Exploration: Understanding the dataset, checking for missing values, and identifying outliers.

Data Preprocessing: Cleaning the data, handling missing values, and encoding categorical variables.

Feature Engineering: Creating lag features, rolling averages, and growth metrics to capture trends.

Model Selection: Using a Random Forest Regressor for its robustness in handling non-linear relationships.

Model Training & Tuning: Optimizing hyperparameters using RandomizedSearchCV.

Evaluation: Assessing model performance using MAE, RMSE, and R² Score.

Key Features
Lag Features: Captures past EV counts to model temporal dependencies.

Rolling Averages: Smooths out short-term fluctuations to highlight trends.

Growth Metrics: Measures the rate of EV adoption over time.

County Encoding: Converts categorical county data into numerical values for model input.


