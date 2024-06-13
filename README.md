# ARDUINO CONTROLLED ROBOTIC ARM

ABSTRACT
The main objective of this project is to control the robotic arm using human gestures The human gestures are sensed with the help of an accelerometer, also known as inertial sensor. A microcontroller is used in the transmitter section. It is coded in such a way that the required actions for the human gesture are done. These sensed signals are processed and then transmitted to the robotic arm at the receiver section using RF transceiver module. Thus the robotic arm performs the required movement.
A remote control system is also used to control the movement of the robot
This system is also uses an RF transceiver module for the wireless communication
This proposed model will be helpful and avoid danger for the people working in hazardous areas.

Gesture recognition technology is used to control the robotic arm. Gesture recognition is a topic in computer science and language technology with the goal of interpreting human gestures via mathematical algorithms.Gesture recognition enables human to communicate with the machine and interact without any mechanical devices.


Literature survey
Various researches have been made by different researches for developing this project. However, they serve a different application and have different technologies implemented
Jorge Kazacos Winter has developed android controlled robot automation. Main aim of his project was the transfer of information wirelessly between a Smartphone and the robot and developing the robot and its communication system underneath a low price and open source philosophy. He used 3D design technique to style the structure of the robot with the facilitation of parametrical modeling software. 
M. Selvam  in his paper has design to develop a robotic system which has a wireless camera attached to the surveillance. Bluetooth was implemented in his project for providing connection between robot and smart phone. Wireless night vision camera was used for providing the robot surveillance. The video which is recorded by camera is then transmitted to TV unit through radio frequency signal. He used 8051 micro-controllers for the robotic 

Objectives
The important objectives that are associated in installing of robotic systems:
Saving of manpower.
Improved quality and efficiency.
Save human’s life.(in some cases such as industrial work)

Our main objective is that it shoul be able  to work in any hostile environment.



Hardware and Software 
These are some of the hardwares that we might use:
Gesture Recognition System,Remote Control System,Sensors,Accelerometer,Arduino Uno
RF Module,HT12 Encoder and Decoder 
Gesture Recognition System:The robotic arm is controlled by Gesture recognition system. Inertial sensors are used to recognize the human gestures and those actions are replicated by the robotic arm.This arm can be controlled from a long distance using RF module. The transmitter section consists of inertial sensors to sense the human gestures, Arduino Uno and RF transmitter module.The receiver section consists of RF receiver module, motor driver, relays and DC motors.The Arduino Uno reads the analog output values from the accelerometer and converts the analog value to respective digital value. The digital values are processed by the Arduino Uno and send to the RF transmitter which is received by the Receiver and is processed at the receiver end which drives the motor to a particular direction.

2.Remote Control System :Wireless remote control system is used to control the mobility of the system. The switches are used to control the movements wirelessly using RF Module. This RF module consists of an RF Transmitter and an RF Receiver. An RF transmitter receives serial data and transmits it wirelessly through RF with its antenna connected at pin 4.The RF module is used along with a pair of encoder and decoder.
3.  Sensors: temperature sensor are interfaced with Arduino Uno board to provide the additional feature to the system.The temperature sensor is used to sense the surrounding temperature and prevent the system from damages
4.RF Module:RF stands for radio frequency. It is available in different operating frequencies and with different operating range.Transmitter receives serial data and transmits RF signal wirelessly to the receiver through this antenna.
5. HT12 Encoder and Decoder :The HT12E encoder are 12 bit encoders that is they have 8 address bits and 4 data bits. It encodes the 12-bit parallel data into serial for transmission through an RF transmitter. Each of the address pins (A0 to A7) are connected to a switch.HT12D converts the serial input into parallel outputs.decodes the serial addresses and data received by RF receiver into parallel data and sends them to output data pins. The serial input data is compared with the local addresses three times continuously and is only decoded when no error or unmatched codes are found. A valid transmission in indicated by a high signal at VT pin.

HARDWARE REQUIREMENTS
Accelerometer :Accelerometer sensors are used to measure the tilt in x and y planes and convert it into analog signals. ADXL335
Arduino Uno: The Uno is a microcontroller board based on the ATmega328P.It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz Arduino consists of both a physical programmable circuit board and a piece of software, or IDE (Integrated Development Environment) that runs on your computer, used to write and upload computer code to the physical board. It is flexible, easy to use hardware and software. Arduino Uno can sense the environment by receiving input from a variety of sensors and can affect its surroundings by controlling lights, motors, and other actuators.


Major outcomes and application of the projects

Some of the advantages are : Automatic grounding of high voltage system.
Retrieving suspicious objects without endangering humans
And major outcomes of the project are:Robot arms work with an outside user or by performing predetermined commandsNowadays, the most developed field of robot arms in every field is the industry and medicine sector. Designed and realized in the project, the robot arm has the ability to move in 4 axis directions with 5 servo motors. 
 Now-a-days robotic arm is used in various areas such as military, defense, medical surgeries, pick and place function in industrial automation applications. Based on the gesture of human hands the robotic arm moves and performs the task and this system replicates the actions of human hand
But basically with our project we can achieve maximum upto picking up nearby things and avoiding obstacles in its path
