# Sea-border-alert-system

we are creating 2 border alert system models here in our project. Its basically an IOT based project. one model is done using gps nad teh other model is done using RSSI.

Implementation: https://drive.google.com/file/d/1OWoU61Zn1X7K1D9CVUm5TehjQIQ9kabR/view?usp=sharing
########################################################

1st sea border alert system using gps module

#######################################################

##components required:

*Arduino uno

*buzzer

*12v DC motor

*16 x 2 LCD Display

*Gps Module

*Bread Board

*adaptor

*Jumperires for connecting the components.

## Steps to follow.
* so this arduino uno is a microcontroller which acts and a sandwich between the hardware and the software components.

* take a jumper wire and connect 5v power supply from arduino to bread board, now take another jumper and connect the ground terminal of arduino uno to breadboard again.

* we are doing this step, as we need power supply port and ground port for multiple components.

* refer the gps_module_connection.png image to connect the hardware part.

* once that connection is done, install arduino ide software and connect your arduino board 
with your Laptop[using USB AB cable] where you have installed the arduino ide software. 

* In arduino ide software go to ->tools ->board and make sure your arduino board is connected to teh software.

* copy paste the "sea border alert system using_gps_module" code in the software and upload the code to your arduino uno board[using USB AB cable].

Note:
I have used different border values according to my location, so kindly change the stored border values, according to your location and execute.


#######################################################

model using RSSI model


#######################################################
## Steps to follow.

* Uses and Installation

* Unzip the files

* Upload the code into ArduinoUno

* Follow the Connection

* Enable the wifi  hotspot, and Power On the System 

* Open the ip address in web browser displayed in the LCD

* Take the device away from the system to view the Safe zone,Moderate zone,Danger Zone.

* Open the Adafruit.io website to see the location (Latitude and Longitude)


