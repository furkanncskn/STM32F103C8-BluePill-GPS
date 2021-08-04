# STM32F103C8-BluePill-GPS

Data received from the GPS NEO-6MV2 sensor.

In the project file, UART communication with Arduino and a led lighting have been implemented to be used for testing purposes.

Timer was created to receive NMEA data from GPS and used in UART interrupt mode. Incoming data is sent to Arduino a different 
UART channel. If the data is successfully transmitted to the Arduino, the led is turned on, if the transmission fails, the led is 
turned off.
