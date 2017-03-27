# Sensor processing
Code for processors on the hyperloop pod that deal with sensor data. There are three processors that handle specific sensor groups
(halleffect, pneumatics and PED) and another central processor that handles processing of smaller sensors that are not as critical 
as well as sensor fusion. Data is sent between the processors over SPI. Data is also sent and recieved by the central arduino with a 
raspberry pi for saving data on the server as well as recieving commands.

