# Pressure-Sensor-Sock
  The Pressure-Sensor sock will be used to help with identifying pressure distribution imbalances when preforming a squat. This will hopefully eliminate some knee and/or back issues that can be identified by improper weight distribution. This will be done with the use of 3 force-sensors distributed to the approxiamte points of weight placement along with a RGB. This color scheme will play a role is the sens e that green will be in +/- 10% across the sensors, yellow will be +/-10% to +/- 25% and red being else. 

## Hardware Components
  -1x Arduino UNO (From Univeristy of regina bookstore, or can be found on SparkFun https://www.sparkfun.com/products/11021)
  
  -3x Force resistant sensors  (acquired form SparkFun https://www.sparkfun.com/products/9375)
  
  -2x Breadboard (acquired form SparkFun https://www.sparkfun.com/products/12615)
  
  -3x 560 Ohm resistors (acquired form SparkFun https://www.sparkfun.com https://www.sparkfun.com/search/results?term=+resistors)
  
  -3x 1k Ohm resistors (acquired form SparkFun https://www.sparkfun.com https://www.sparkfun.com/search/results?term=+resistors)
  
  -1x Solder Iron with 25V recommended (Local Canadian Tire http://www.canadiantire.ca/en/pdp/mastercraft-solder-station-0586301p.html#srp is what I used)
  
## Project Schematic 

[schematic for gothub.pdf](https://github.com/Mcnish15/Pressure-Sensor-Sock/files/1913147/schematic.for.gothub.pdf)



## Getting Started
Step 1 
  -Connect 3 sensors in a parallel series with 560 Ohm resistors  and connect to Analog pins 0, 1  and 2.
  
  
Step 2 
  -Test sensors on Arduino Serial Monitor and/or Serial Plotter
  
  
Step 3
  -resistor selection can be changed if your are wanted to work will smaller or larger voltage values 
  
  
Step 4
  -Wire RBG on Digital pins 8, 9, 10 with 1K Ohm resistors. 
  
  
Step 5
  -Test RBG with setColor to insure RGB is grounded properly 
  
  
Step 6
  -Decide on parameters you are wanting to use for weight distribution calibration. I used 0-10% the RGB will show green, 10-25% the RGB will show yellow, and else will show red. This can be adjusted within the else if statements throguhout. 
  
  
Step 7
  -Sodler sensors onto wire once calibrated
  
  
Step 8 
  -place the 3 sensors at the 3 main pressure points on your feet. 
  

## Prerequisites
  -Sodlering experience
    -The sensors are very easy to overheat so i would advise that if you are not experienced with soldering to practice on an               old electronic laying around your house. 
  


## Software Components
  -Arduino IDE
  
  -No additonal libraries needed 

## Data demo
  -Arduino Serial Plotter
  [Serial Plotter Data example.pdf](https://github.com/Mcnish15/Pressure-Sensor-Sock/files/1913168/Serial.Plotter.Data.example.pdf)
  
  
  Serial Monitor [Serial Monitor Data example .pdf](https://github.com/Mcnish15/Pressure-Sensor-Sock/files/1913173/Serial.Monitor.Data.example.pdf)

## Final Code  [Github Code.docx](https://github.com/Mcnish15/Pressure-Sensor-Sock/files/1913190/Github.Code.docx)

## Built With
  Arduino UNO
   - Arduino 1.8.5

## Authors

Mitchell McNish


## Acknowledgments

Thanks you to Juliette van der Pas who has a similar idea allowing me to branch off for my Computer Science 207 class project! This can be found at https://www.hackster.io/Juliette/a-diy-smart-insole-to-check-your-pressure-distribution-a5ceae
