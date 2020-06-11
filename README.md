# Density-based-traffic-control-system-with-emergency-vehicle-assistance
4th sem Microprocessor and Computer Architecture project on the topic  "Density based traffic control system with emergency vehicle assistance" implemented using Arduino.

Requirements:

Arduino Mega 2560

4 Ultrasonic sensors HC-SR04


LEDS(4 Red,4 Yellow,4 Green,4 Blue)

4 RFID transmitter and receiver MFRC 522

Jumper Wires

Resistors

The working of the project is divided into four steps

-If there is traffic at all the signals, then the system will work normally by controlling the signals one by one.

-If there is no traffic near a signal, then the system will skip this signal and will move on to the next one. For example, if there is no vehicle at signal 2, 3 and currently the system is allowing vehicles at signal 1 to pass. Then after signal 1, the system will move on to signal 4 skipping signal 2 and 3.

-If there is no traffic at all the 4 signals, system will stop at the current signal and will only move on the next signal if there will be traffic at any other signal.

-In case an emergency vehicle is detected by the rfid receiver that signal is immediately given green signal along with a blue flashing light to indicate the presence of  emergency vehicle so that other vehicles can make way.


Images of working model:

<img src="https://github.com/Ajitesh27/Density-based-traffic-control-system-with-emergency-vehicle-assistance/blob/master/images/2.jpg"/>
<img src="https://github.com/Ajitesh27/Density-based-traffic-control-system-with-emergency-vehicle-assistance/blob/master/images/3.jpg"/>
<img src="https://github.com/Ajitesh27/Density-based-traffic-control-system-with-emergency-vehicle-assistance/blob/master/images/1.jpg"/>
<img src="https://github.com/Ajitesh27/Density-based-traffic-control-system-with-emergency-vehicle-assistance/blob/master/images/4.jpg"/>
