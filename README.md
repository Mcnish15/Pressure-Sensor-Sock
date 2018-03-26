# Pressure-Sensor-Sock
  The Pressure-Sensor sock will be used to help with identifying pressure distribution imbalances when preforming a squat. This will hopefully eliminate some knee and/or back issues that can be identified by improper weight distribution. This will be done with the use of 6 force-sensors distributed to the approxiamte poiunts of weight placement along witha 3 LED syatem green, yellow and red. This color scheme will play a role is the sens e that green will be in +/- 10% across the sensors, yellow will be +/-10% to +/- 25% and red being else. 

Materials
  1x Arduino UNO
  6x FSP
  1x Breadboard
  
Project Schematic 


Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Prerequisites
  


Installing
A step by step series of examples that tell you have to get a development env running
  Download Thinger.io
    Incluide into Arduino library
      This will allow for information to be transfered to an online data base showing numerical values for the forces applied
        You can then calibrate your sensors to be within error
  Download Adafruiit Circuit Playground 
    add:
      #include <Adafruit_CircuitPlayground.h>
      #include <Wire.h>
      #include <SPI.h>

Data demo

Final Code

Built With
  Arduino UNO
  Arduino 1.8.5

Versioning
We use SemVer for versioning. For the versions available, see the tags on this repository.

Authors
Mitchell McNish

License


Acknowledgments
Thanks you to Juliette van der Pas who has a similar idea allowing me to branch off for my Computer Science 207 class project! This can be found at https://www.hackster.io/Juliette/a-diy-smart-insole-to-check-your-pressure-distribution-a5ceae
