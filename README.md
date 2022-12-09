# Particle Detection and Prediction using CNNs and LSTMs

This project is based on Convolutional and Recurrent neural networks in order to generate particle data, detect particles, and finally forecast their future movements.
* Generate synthetic data.
* Built CNN and CNN-LSTM models to detect particle movements.
* Built LSTM model (2 LSTMs of 128 and 64 units) to forecast the particle position, achieved MSE =  0.24 and 0.18 for X and Y coordinates respectively.


# Resources Used
* Python Version: 3.7
* CUDA Toolkit 11.5.119 
* Packages and Libraries: pandas, numpy, matplotlib, sklearn, keras, math.


# Results:

Particle Detection: 

CNN Model              | CNN-LSTM Model   
:-------------------------:|:-------------------------:
![](https://github.com/sophiajwagner/particle-detection-and-prediction/blob/main/img/det_model1_output.PNG)  |  ![](https://github.com/sophiajwagner/particle-detection-and-prediction/blob/main/img/det_model2_output.PNG)

LSTM model:

![image 1](https://github.com/sophiajwagner/particle-detection-and-prediction/blob/main/img/Captureds.PNG)

Forecasting Results:

X-coordinates              | Y-coordinates   
:-------------------------:|:-------------------------:
![](https://github.com/sophiajwagner/particle-detection-and-prediction/blob/main/forecasting_results_xcoord.png)  |  ![](https://github.com/sophiajwagner/particle-detection-and-prediction/blob/main/forecasting_results_ycoord.png)
