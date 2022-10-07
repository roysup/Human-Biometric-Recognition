# Human-Biometric-Recognition

The code implements gender recognition utilising wearable sensor data for multiple activities and sensor placements. 

A number of approached were tested as part of overall research to determine the sensor, activity, and combinations and model architecture for obtaining the best results.
These included implementing the state-of-the-art model (autoencoders) instead of 1D CNN, or leaving out certain signal features in different directions, or leaving out gyroscope readings altogether, or fusing readings from multiple sensors for each activity via a multi-head 1D CNN. 
