# Electronics Projects 

## 1) Finger print based Security System 

 <img src="https://www.amvitech.com/amvitechimages/IMG_20161007_145452_HDR.jpg" width="700" height="400">

A fingerprint security system is a system which uses biometric data from the user in order to identify unique individuals interacting with the system. The fingerprint is sensed here using an optical finger print sensor. The components required for this project are an optical fingerprint sensor, a microcontroller of the 8051 family, buzzer, relay ,keypad and an LCD display. In order to configure this system ,we run this system in the settings mode, where the system takes in fingerprint data of different users. Then after collecting the fingerprint data, the system is used in the normal mode where the user gives his/her fingerprint and the system compares this fingerprint to the previous data collected. If the fingerprint matches with any of the previous data, it gives an OK signal through the LED screen. If the fingerprint doesn’t match, then the system outputs an ERROR message. The keypad has three keys which can be used to toggle the different modes of the system. For example – The first key tells the system to collect fingerprint data, the second key is the mode where the system compares a new fingerprint with the existing data and the third key is used to reset all previously collected fingerprint data. The keypad 1 and 3 can be password protected so that only the admin is able to reset/change the settings of the device.


## 2) Sun Tracking Solar Panel

A sun tracking solar panel is a system which adjusts the position of a solar panel according to the position of the Sun above the panel at different times of the day. The system consists of two Light dependent resistors (LDRs), a solar panel, a servo motor and an ATmega328 microcontroller along with resistors, capacitors, connecting wires and a breadboard/ PCB designed for the circuit. The LDRs are placed at the sides of the solar panel. When light falls on an LDR, the resistance is decreased. Therefore when an LDR on one side has a lower resistance than the other, the servo- motor connected to the solar panel rotates the panel in the direction of the LDR having lower resistance in order to increase the light falling on the solar panel. When both LDRs have the same intensity of light falling on them, then the servo motor stops rotating the panel. The Solar panel is placed on a flat cardboard surface which is connected to the servo motor and the motor rotates the panel on the cardboard.


## 3) Human Detection Robot 

![Transmitter circuit](https://www.electronicshub.org/wp-content/uploads/2014/09/Human-Detection-Robot-Circuit-Diagram-Transmitter-Section.jpg)

![Receiver Circuit](https://www.electronicshub.org/wp-content/uploads/2014/09/Human-Detection-Robot-Circuit-Diagram-Receiver-Section.jpg)

Human detection robot is a moving system which used to detect the presence of Human beings. This has high applications for accident rescue teams where they identify humans in the disaster zone in order to rescue them. As the system is a wireless robot, the system consists of two circuits, the transmitter circuit and the receiver circuit. The transmitter circuit consists of an RF transmitter, a MAX232 IC and a DB9 connector connected to a PC. The MAX 232 is used for serial communication. The receiver circuit consists of AT89c51 microcontroller which belongs to the family of 8051 microcontrollers, an RF receiver to receive the signal from the transmitter, PIR sensor, L293D motor driver and motor components of the robot. The PIR sensor is used to detect human presence. Humans beings emit infrared radiations of low wavelength. The PIR sensor detects these IR radiations and hence detects humans in a region. The L293D is a motor driver IC which is required to drive the motors and to eliminate any back EMF generated. This system can also be used for military purposes to detect injured soldiers during wars.


## 4) Automatic Room light Controller

This project describes the system which is used to automatically switch room lights on/off as a person walks in/out of the room. The components used are an ATMEGA16A microcontroller, IR sensors, LCD display, Step down transformer, relay unit and circuit components such as a power supply, a PCB, resistors  and capacitors.  In the setup, the IR sensors monitor the persons moving in and out of the room and transmits the IR signals. The microprocessor continuously tracks the persons in the room. The first IR sensor tracks movement of people into the room and therefore the microcontroller increments the number of people by 1 whereas the second microcontroller tracks movement of people out of the room and hence the microcontroller decrements the number of people by one when this IR sensor senses a person. Based on the number of persons, the microcontroller decides whether to switch on the LEDs or not. During parties where there a large number of people, this system can be modified in order to switch on different amount of lights based on the different amount of people present in the room. For example- Switch on 4 lights if more than 10 people are in a room, Switch off all lights when there are 0 persons in the


## 5) Wireless Stethoscope

Many heart diseases and conditions are often predicted by listening to the sounds the heart makes due to its beating. This project aims to build a wireless stethoscope by using an Arduino UNO microcontroller. We first take a stethoscope and connect a microscope to the chest piece of the stethoscope in order to obtain the sounds of the heart of the patient. Next we use an op-amp in order to amplify the signal from the microphone which then can be read by the Arduino. Before processing the signal, we use a low pass filter which eliminates unnecessary noise in order to get only the heartbeat sound from the patient. The components for the system are an Arduino UNO, a HC-05 Bluetooth module, ADC,a microphone, NE5532 Op-Amp-1,Power supply, resistors and capacitors. First, the heartbeat is picked up by a condenser microphone. Next we have an amplifier which amplifies the system by 100x  . Now, the amplified signal is passed through the low-pass filter which rejects all the high-frequency noise. Then, with the help of an ADC, we calculate the heartbeat from the signal and send the data by using a wireless Bluetooth module.


## 6) Portable Weather Station

A weather station gives information about the weather in our current surroundings. This includes displaying the temperature, humidity and the pressure in our surroundings. Different sensors are used to measures the different parameters. The DHT11 sensor measures the temperature and humidity parameters. We can also calculate other parameters such as relative humidity and dew point using these measured parameters. The BMP sensor can be used to detect altitude and measure the vertical velocity. The signals from these sensors are then amplified and connected and the microcontroller (Arduino Nano/UNO) then displays the data on the LCD screen of the portable weather station. We can also add additional code which can help us to predict incoming rain by measuring the humidity and comparing it with the average humidity over the previous days. Also in order to hold the components, a small box displaying the LCD made of wood/plastic materials can be designed.


## 7) Raspberry Pi Internet Radio and Streaming Station

![Server](https://circuitdigest.com/sites/default/files/inlineimages/u3/Raspberry-Pi-Internet-Radio.jpg)

Using Raspberry pi, we can set-up a streaming station using DarkIce and Icecast. DarkIce and Icecast are raspberry Pi packages which are used for audio recording ,encoding and streaming. DarkIce is a live audio streamer that records audio from an audio interface such as a microphone, encodes it and sends it to a streaming server. DarkIce can encode the audio in various formats such as MP3,MP2,AAc etc. It then sends the encoded audio to a streaming server such as Icecast. Icecast is an audio/video streaming media server that supports various file formats such as MP3,WebM etc. In order to set-up the system, first we need to install the two packages on the Raspberry Pi. When configuring Icecast, we provide the server details such as the hostname. Next, after configuring the Icecast, we now configure DarkIce with different options such as file format and internet buffer rate. Now after setting up and configuring them, we start the raspberry Pi, and can use the raspberry Pi’s IP address to open up the web in order to see the Icecast streaming. Thus, using these we can set up a streaming station which can be used as a jukebox, radio station etc.



