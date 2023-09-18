# Kalman-Filters
This GitHub repository contains an implementation of a Kalman filter for sensor data fusion. Kalman filtering is used for estimating the state of a system by combining noisy sensor measurements with a predictive model. This project showcases the application of Kalman filtering to predict and enhance position and velocity data.

## Key Features

- Sensor data fusion for position and velocity estimation.
- Kalman filter implementation with process and measurement noise.
- Visualization of sensor data, predicted values, and covariance matrices.
- An example dataset ("kalmann.txt") to demonstrate the filter's performance.

## Input Data Explanation

The input data for this project is stored in a .txt file, which you can find at data folder. The file follows the following format:

- **Line 1:** Initial position (x, y)
- **From Line 2 onward:** Data for each state
  - Position (x, y)
  - Average velocity (vel x, vel y)

The average velocity (vel x, vel y) represents the average velocity between the previous state and the current state.
