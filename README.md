# IoT-based-Agriculture-Monitoring-and-Automatic-Water-System

This project aims at simplifying the way current agriculture system works by eliminating manual labor which decreases the cost of production.
It also eliminates implementation charges and other minor irrigation charges.
We use Arduino , a sim card and a bunch of low-cost sensors making this affordable with minimalistic technology

AIM AND OBJECTIVE:
The main objective of this project is to provide an automatic irrigation system thereby saving time, money & power of the farmer. The traditional farm-land irrigation techniques require manual intervention. With the automated technology of irrigation the human intervention can be minimized. 
Collecting crucial agriculture data like Temperature , Air quality , Sunlight , Humidity in a graphical way.
Monitoring the soil moisture and automatically irrigating the land with the application designed.

METHODOLOGY-1 :
Soil moisture sensor and Bluetooth module are connected to Arduino UNO board through jumper wires and breadboard.
Soil moisture sensor will sense the dankness of soil and through Bluetooth module the data will be transferred to designed application to act upon that data. 
A threshold value has been set, both minimum and maximum, so that whenever the measured value crosses the predefined threshold value the motor will be switched on/off automatically.
A 5V motor pump has been used for this project as this is a mini prototype model and Arduino that is used in this project can provide maximum of 5V power.

Components used :

LM393  LIGHT SENSOR MODULE
MQ 135 AIR QUALITY/GAS SENSOR
DHT11 SENSOR
GSM MODULE SIM 900A
SOIL MOISTURE SENSOR
HC-05 Bluetooth Module 
ARDUINO UNO


Thingspeak Server : 
Thingspeak is an open source IOT application to store and retrieve data from things. It displays the data from the things (here sensors) in a graphical way.
It generates an unique API keys which is needs to be uploaded during the programming of Arduino , so that it connects to the GSM module used which is connected to internet. 

Working:
With the complete hardware setup as in the circuit and software programming for the Arduino , all the sensors data gets displayed in the LCD display.
As the project gets connected to internet , the data is sent to the Thingspeak server and by opening the Thingspeak account one can check the collected data in a graphical way  with respect to the time.
One can easily analyze the data to make sensible changes in the supplied resources to obtain high yield.

Results :
![image](https://github.com/ChandraLekha559/IoT-based-Agriculture-Monitoring-and-Automatic-Water-System/assets/140607268/711c5054-165c-4328-a4fa-f87b06d1b38a)

![image](https://github.com/ChandraLekha559/IoT-based-Agriculture-Monitoring-and-Automatic-Water-System/assets/140607268/8ef7a5b3-dd62-4ee9-98ca-a50f1e01ab17)

