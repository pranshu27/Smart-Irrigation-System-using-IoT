# Smart-Irrigation-System-using-IoT

## Problem Description
Aravind is an ambitious farmer who wants to improve the yields from his farmland. While looking for ways to improve the yields, he came across tech buzzwords like the Internet of Things and Machine Learning. He wants to try them out to build an intelligent irrigation system for his field. The irrigation system he wants to build contains servo motors that control the water supply to the farm, based on the present humidity, temperature levels in the farm. Using sensor data, Aravind wants to build a machine learning model that predicts how much water (in percentage) should be supplied to his farm. Aravind also does not want to water the plants during nighttime. However, Aravind is good at farming and does not have much experience building Machine learning models and IoT systems. So, build an irrigation system for Aravind using the IoT simulator at this link (https://wokwi.com/arduino/new?template=arduino-mega) and design a farm irrigation circuit using Arduino Mega board.

Identify the required sensors needed to build the irrigation system based on Aravind’s requirements from the list of sensors provided by the simulator. The irrigation system should feed the sensor readings to a machine learning model and produce the correct signal (% of water flow) to control the water supply. Use a servo motor to control the water supply. The farm irrigation system should contain four sensor units such that each unit sense temperature and humidity values. These values will be provided to ML model on the Arduino board to predict the water flow in percentage. Then the water flow percentage will be provided as input to the servo motor (Map the percentage values with servo motor rotation 0◦ to 180◦). The sensor values from each sensor unit should control a servo motor. Also, display the % of water flow that is fed as input to servo motors on an LCD.

### NOTE:
- The simulation is done using Wokwi simulator: <https://wokwi.com/projects/314086016050790976>

- Video Demonstration of Smart Irrigation System:  <https://www.youtube.com/watch?v=3-aRQZGpVWE&feature=youtu.be>

- The file "weights.txt" contains the obtained weigths after training the MLP model 

- Below is the image of the simulation using Wokwi: ![None](https://github.com/pranshu27/Smart-Irrigation-System-using-IoT/blob/main/Screenshot%202022-07-26%20at%207.22.08%20PM.png?raw=true "Wokwi")


