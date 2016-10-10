# Simple Robot Arm Controller
A project for the control of a simple robotic arm with an Arduino. 

This project is based  around control of a MeArm robotic arm with an Arduino Uno. 
It is separated into two main components, hardware and software. 

## Hardware Overview
This project includes an Arduino shield that is capable of controlling 
all 4 degrees of freedom the MeArm has. It also has the capability
to read potentiometer values for use with a "training" mode. Input 
buttons, status LEDs, and a voltage regulator circuit will also be
placed on the board.

## Software Overview
The software for this project is designed either to run standalone
on the arduino or in conjunction with companion software on a PC.
Software features include a training mode, inverse kinematics, and
serial control. Training mode utilizes a model of the arm with 
potentiometers in place of servo's. This model is manipulated and the arm
mirrors the motions. 
