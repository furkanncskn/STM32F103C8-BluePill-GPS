# STM32F103C8-BluePill-GPS

Data received from the GPS NEO-6MV2 sensor.

In the project file, UART communication with Arduino and a led lighting have been implemented to be used for testing purposes.

Timer was created to receive NMEA data from GPS and used in UART interrupt mode. Incoming data is sent to Arduino a different 
UART channel. If the data is successfully transmitted to the Arduino, the led is turned on, if the transmission fails, the led is 
turned off.

> 
![photo_2021-08-04_17-00-25](https://user-images.githubusercontent.com/75426545/128215280-db0f5e59-8acf-4e6d-8a70-4972671b3232.jpg)
![photo_2021-08-04_19-06-16](https://user-images.githubusercontent.com/75426545/128215295-2d4394c4-2702-44e5-acef-188a51ad3fa5.jpg)
