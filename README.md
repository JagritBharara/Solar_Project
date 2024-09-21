# Solar_Project
Overview
This project demonstrates a machine learning pipeline for predicting solar radiation using a transformer-based neural network model. The dataset contains monthly solar radiation data, and the model is built using Keras and TensorFlow. A transformer-like architecture is employed to incorporate both time-series (month) and numerical features to predict future solar radiation values.

Dataset
The dataset, solar_radiation.csv, contains the following columns:

year: Year of data collection.
month: Month of data collection (Categorical).
H(h)_m: Solar radiation on the horizontal plane.
H(i_opt)_m: Optimal solar radiation.
H(i)_m: Solar radiation on inclined surfaces.
Hb(n)_m: Beam solar radiation.
Kd: Diffuse radiation factor.
T2m: Temperature at 2 meters above the ground.
