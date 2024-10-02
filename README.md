# REDSBU-PV-Power-Forecasting

This project focuses on forecasting photovoltaic (PV) power generation using various machine learning models. The input dataset includes features such as solar irradiation, wind velocity, ambient temperature, module temperature, and timestamps (datetime). The goal is to predict future PV power generation using models like Gradient Boosting Machines (XGBoost/LightGBM), Random Forest, Artificial Neural Networks (ANN), and Long Short-Term Memory (LSTM) networks.

# Dataset
The dataset used in this project contains the following columns:

<b>Datetime:</b>  Timestamp of the measurement.

<b>IntSolIrr (W/m^2):</b> Solar irradiation at a given time.

<b>WindVel m/s (m/s):</b> Wind velocity near the PV panels.

<b>TmpAmb C (°C):</b> Temperature in the surroundings of the PV system.

<b>TmpMdul C (°C):</b> Temperature of the PV modules.

<b>A.Ms.Amp (A):</b> The output PV Current at the given time.

<b>A.Ms.Vol (V):</b> The output PV Voltage at the given time.

<b>A.Ms.Watt (W):</b> The actual PV power generation at the given time (target variable).
