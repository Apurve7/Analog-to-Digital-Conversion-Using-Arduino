# Analog-to-Digital-Conversion-Using-Arduino

This project uses an Arduino and a DHT11 sensor to measure ambient temperature and humidity, displaying the readings on your computer.

Functionality 
The Arduino code periodically reads data from the DHT11 sensor every two seconds. It then transmits these readings over the USB connection to be displayed in the Arduino IDE's Serial Monitor.

Sensor Reading: The SimpleDHT library is used to handle the communication with the DHT11 sensor.

Serial Output: The program initializes a serial connection at a 9600 baud rate to send the formatted temperature (in Celsius) and humidity (as a percentage) data to your computer.

Hardware Requirements 🔩
Arduino Uno (or any compatible board)

DHT11 Temperature and Humidity Sensor

Breadboard

Jumper Wires



Software & Library Requirements 
Arduino IDE

SimpleDHT Library: This code requires the SimpleDHT library by winlinvip. You can install it directly from the Arduino IDE:

Go to Sketch > Include Library > Manage Libraries...

Search for "SimpleDHT".

Find the one by winlinvip and click Install.

Circuit and Connections 🔌
The connection is simple. Most DHT11 modules have three pins: VCC (Power), GND (Ground), and DATA.

DHT11 Pin	Arduino Pin
VCC / +	5V
DATA / OUT	A0
GND / -	GND



