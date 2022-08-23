# Smart-Irrigation-System-using-IoT

1. The idea was to decrease water usage by only watering when required, when temperatures and humidity are low.
2. Trained a 2 - layer ML Perceptron regression model on data that used IoT sensors (DHT22) to predict water flow %.
3. We achieved R2 regression score of 0.8707 and MAPE(Mean Absolute Percent Error) of less than 1%(0.748).
4. In order to turn off the irrigation system at night, we used a photoresistor(LDR) sensor to detect light.
5. This functionality was implemented on an Arduino Mega 2560 board and simulated on Wokwi.

### NOTE:
- The simulation is done using Wokwi simulator: <https://wokwi.com/projects/314086016050790976>

- Video Demonstration of Smart Irrigation System:  <https://www.youtube.com/watch?v=3-aRQZGpVWE&feature=youtu.be>

- The file "weights.txt" contains the obtained weigths after training the MLP model 

- Below is the image of the simulation using Wokwi: ![None](https://github.com/pranshu27/Smart-Irrigation-System-using-IoT/blob/main/Screenshot%202022-07-26%20at%207.22.08%20PM.png?raw=true "Wokwi")


