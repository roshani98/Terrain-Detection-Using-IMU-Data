# Terrain-Detection-Using-IMU-Data

The goal of the project was to identify and classify the terrain a person is walking on. This is helpful in designing artificial prosthetics which would adjust
according to the terrain a person is walking on.

## DATASET
<br/>
[B. Zhong, R. L. d. Silva, M. Li, H. Huang and E. Lobaton, "Environmental Context Prediction for Lower Limb Prostheses With Uncertainty Quantification," in IEEE Transactions on Automation Science and Engineering, vol. 18, no. 2, pp. 458-470, April 2021, doi: 10.1109/TASE.2020.2993399.](https://ieeexplore.ieee.org/document/9098903)

## METHODOLOGY
To predict a time series data we have used the method of implementing a CNN-LSTM by mapping the data in a 3-D space and passing the features as channels to the CNN for feature extraction. We then pass these features into the LSTM Model and predict the terrain
