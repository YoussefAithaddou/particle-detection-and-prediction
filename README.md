# Particle Detection and Prediction using CNNs and LSTMs

In this project is based on Concolutional and Recurrent neural networks in order to generate particle data, then we detect and track particles, and finnaly forecast their future movements.
* Generate synthetic data.
* Built CNN and CNN-LSTM models to detect and track particle movements.
* Built LSTM model (2 LSTMs of 128 and 64 units) to forecast the particle position, achieved MSE =  0.24 and 0.18 for X and Y coordinates respectively.


# Resources Used
* Python Version: 3.7
* CUDA Toolkit 11.5.119 
* Packages and Libraries: pandas, numpy, matplotlib, sklearn, keras, math.


# Results:

LSTM model:

![image 1](https://github.com/YoussefAithaddou/particle-detection-and-prediction/blob/main/Captureds.PNG)

Forecasting Results:

X-coordinates              | Y-coordinates   
:-------------------------:|:-------------------------:
![](https://github.com/YoussefAithaddou/particle-detection-and-prediction/blob/main/download%20(2).png)  |  ![](https://github.com/YoussefAithaddou/particle-detection-and-prediction/blob/main/download%20(1).png)
