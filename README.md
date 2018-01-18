# RTOS-Based-Autonomous-Car

This is an RTOS based Autonomous car project that uses car five micro controller units LPC1758 that communicate with each other using CANBus Communication protocol. 
The tasks of the individual microcontrollers are listed below:

*Master Controller - Contains the algorithm for making decisions of the car navigation based on the input sensor values.
*Distance Sensors Controller - Interfaces with Lidar and Ultrasound sensors to obtain obstacle proximity values
*Geo Controller - Interfaces the GPS and the compass module to obtain the current position and the heading angle 
*Communication/Android Controller - Incorporates the Bluetooth Module for communication with the Android Application
*Motor and I/O controller - Interfaces the motors and LCD dispay module for 

The importanat features of the car include the following:
Android App and LCD interface for the car
Obstacle detection and avoidance using a superior Lidar sensor
Auto speed adjustment to deal with cntrolled speed on inclined planes
GPS Navigation

A complete descriptionof the code is avaiable in the follwing link:
http://www.socialledge.com/sjsu/index.php?title=F17:_Tata_Nano
Video of the project demo:
https://www.youtube.com/watch?v=imzmpYmaIn8
The complete source code is avaiable in the following GitLab Repository:
https://gitlab.com/shivam5594/Autonomous-car/tree/embedded
