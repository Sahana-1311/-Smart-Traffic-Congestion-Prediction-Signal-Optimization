# Smart Traffic Congestion Prediction & Signal Optimization

A machine learning model to predict traffic congestion and optimise signal timings across city corridors.

## Overview
Trained on 50,000+ timestamped traffic records from 12 city corridors. Outperforms linear baseline by 31%.

## Key Features
- Gradient Boosting regressor achieving RMSE of 4.2 vehicles/min
- 14 contextual features engineered: hour, weekday, rainfall flag, school-zone proximity, and more
- Rule-based signal scheduler using predicted density values
- Simulation shows estimated 22% reduction in peak-hour vehicle wait time

## Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib

## Results
- RMSE: 4.2 vehicles/min
- 31% improvement over linear baseline
- 22% estimated reduction in peak-hour wait time
