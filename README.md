# Amit_Embedded_Project
For this project, 2 Microcontrollers (atmega32) are used first one as master and other one is slave.
The folder for master is named"Group-F18" and for slave "SPI_slave".
The user inputs are either "TV_on","TV_off","Washer_on","washer_off". 
The user write the input in the virtual terminal and must type "#" after each input for example "TV_on#" so that the terminal knows the string has finished.
2 Leds connected at portA of the slave represent the TV (PA0) and the Washer (PA3).
LCD connected to slave shows the current situation either "TV is on", "TV is off", "washer is on" or "washer is off".
