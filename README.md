# Human-Biometric-Recognition

The code implements gender recognition utilizing wearable sensor data for multiple activities and sensor placements. 

Several approaches were tested as part of overall research to determine the sensor, activity combinations, and model architecture to obtain the best results.

These included implementing the state-of-the-art model (autoencoders) instead of 1D CNN, leaving out certain signal features in different directions, and leaving out gyroscope readings altogether. 

Finally, two different approaches were undertaken with the 1D CNN model and both accelerometer and gyroscope readings in all three directions.
The first method obtains the gender recognition accuracies for each sensor measuring each activity with a 1D CNN, and the second method fuses readings from multiple sensors for each activity via a multi-head 1D CNN.

