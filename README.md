# REDSBU-PV-Power-Forecasting

This project focuses on forecasting photovoltaic (PV) power generation using various machine learning models. The input dataset includes features such as solar irradiation, wind velocity, ambient temperature, module temperature, and timestamps (datetime). The goal is to predict future PV power generation using models like Gradient Boosting Machines (XGBoost/LightGBM), Random Forest, Artificial Neural Networks (ANN), and Long Short-Term Memory (LSTM) networks.

# Dataset
The dataset used in this project contains the following columns:
<b>datetime:</b>  Timestamp of the measurement.
<b>irradiation:</b> Solar irradiation at a given time.
<b>wind_velocity:</b> Wind velocity near the PV panels.
<b>ambient_temperature:</b> Temperature in the surroundings of the PV system.
<b>module_temperature:</b> Temperature of the PV modules.
<b>pv_power:</b> The actual PV power generation at the given time (target variable).
