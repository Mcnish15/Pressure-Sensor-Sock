# Pressure-Sensor-Sock
  The Pressure-Sensor sock will be used to help with identifying pressure distribution imbalances when preforming a squat. This will hopefully eliminate some knee and/or back issues that can be identified by improper weight distribution. This will be done with the use of 3 force-sensors distributed to the approxiamte points of weight placement along with a RGB. This color scheme will play a role is the sens e that green will be in +/- 10% across the sensors, yellow will be +/-10% to +/- 25% and red being else. 

Materials
  1x Arduino UNO
  3x Force resistant sensors  
  2x Breadboard
  1x Solder Iron
  3x 560 Ohm resistors
  3x 1k Ohm resistors
  
Project Schematic 



Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


Step one 
  -Connect 3 sensors in a parallel series with 560 Ohm resistors  and connect to Analog pins 0, 1  and 2.
  
  
Step 2 
  -Test sensors on Arduino Serial Monitor and/or Serial Plotter
  
  
Step 3
  -resistor selection can be changed if your are wanted to work will smaller or larger voltage values 
  
  
Step 4
  -Wire RBG on Digital pins 8, 9, 10 wiht 1K Ohm resistors. 
  
  
Step 5
  -Test RBG with setColor to insure RGB is grounded properly 
  
  
Step 6
  -Decide on parameters you are wanting to use for weight distribution calibration. I used 0-10% the RGB will show green, 10-25% the RGB will show yellow, and else will show red. This can be adjusted within the else if statements throguhout. 
  
  
Step 7
  -Sodler sensors onto wire once calibrated
  
  
Step 8 
  -place the 3 sensors at the 3 main pressure points on your feet. 
  

Prerequisites
  -Sodlering experience
    -The sensors are very easy to overheat so i would advise that if you are not experienced with soldering to practice on an               old electronic laying around your house. 
  


Installing
  -No additonal libraries needed 

Data demo
  -Display  sensot voltge on Arduino Serial Monitor and Serial Plotter

Final Code

Built With
  Arduino UNO
  Arduino 1.8.5

Authors
Mitchell McNish

License


Acknowledgments
Thanks you to Juliette van der Pas who has a similar idea allowing me to branch off for my Computer Science 207 class project! This can be found at https://www.hackster.io/Juliette/a-diy-smart-insole-to-check-your-pressure-distribution-a5ceae
