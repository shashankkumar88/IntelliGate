# IntelliGate
AI powered crowd management for enclosed spaces

This project deals with counting the number of people entering/exiting in enclosed spaces. The aim of this project is to automate the task of staff in managing the crowd to maintain social distancing protocols. A live feed from Wyze IP Cam is sent to BluePrism Digital Worker for counting people entering/exiting the space. The bot calculates the number of people inside at real-time using computer vision and transmits the data to ThingSpeak IOT channel. The ThinkSpeak IOT triggers a tweet whenever the people count exceeds maximum limit which the staffs can monitor on their mobile devices. An Arduino microcontroller connected with ESP8266 and LCD screen is used to retrieve feed from the ThingSpeak IOT channel to provide visual indication at the entry gate whenever the building has reached its maximum capacity.

## System Architecture
![System Architecture](Images/System Architecture.jpg)
