# Embedded_LTTS_PROJECT

## Smart temperature-controlled car seat using thermoelectric devices 

### Theory
The thermal comfort for children and adults inside the car is a crucial issue to improve as the hot environmental conditions can be irritable and uncomfortable. Being inside an extremely hot car for a prolonged time can lead to major health problems. This paper focuses on the thermal comfort of infants. Traditionally air conditioning systems are used to cool down an infant car seat which is not effective due to the portability and cooling duration. In this paper, heat relief for the child is researched using a thermoelectric cooling system. This paper reviews various factors concerning the development of a temperature-controlled infant car seat. This study focuses on the health and safety of children inside the cars, the subjective needs of the parent, heat management in the car cabin environment, thermoelectric modeling, and the methods for precise temperature control for effective thermoelectric cooling. In-depth research has been conducted on the contributions of other researchers on the thermoelectric cooling system in a car. The thermoelectric device in the infant car seat was tested in thermal simulation.


### Simulation

The Coding part of the application is written in C language in CODEBLOCKS IDE and the simulation of working product is shown in SimulIDE software. 
Two images are shown below where in the 1st image shows the status of the simulation when the system is OFF and the second image shows the status of the system when it is ON. 

#### ON
![ON](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Simulation.gif)

#### OFF
![OFF](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Simulation_OFF.PNG)



### Functionality 

* When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
* Next the analog input from the temperature sensor is received and digitized.
* The digitized temperature input is visualized using Pulse Width Modulation.
* The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.




### CI and Code Quality

|Build|Cppcheck|Codacy|
|:--:|:--:|:--:|
