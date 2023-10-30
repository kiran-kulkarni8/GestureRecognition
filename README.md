# GestureRecognition
This project aims at developing a mobile robotic arm, which can be controlled by hand gestures. 
We will achieve this through a device camera that will capture the hand gestures accurately. 
Developing a gesture recognition system that can interpret hand movements captured by the camera can be implemented by opencv library that includes pre-trained models for hand gesture recognition.
This typically involves computer vision techniques, machine learning algorithms, or a combination of both.
This enables the translation of those movements and gestures into commands that can be transferred using some protocols to a Jetson nano; then be interfaced with the robotic arm.

Basically, map each gesture to the corresponding movement or action that the robotic arm should perform.

We’ll then integrate the gesture control system with the robotic arm hardware by implementing the necessary communication protocol (serial communication , Ethernet) on the Jetson Nano to establish a connection with the robotic arm's control system.

*Rover programming

Simulated the rover using Mission Planner

Through DroneKit-Python, commands were given to move the rover

*Rover and Robotic Arm designing 
Designed the rover to place all the components properly.
Built the 6 DOF Robotic Arm
*Robotic arm programming
Programmed the servo motors to move the arm in a specific way and angles using SMBus.
*Hand gesture recognition
Building a model to recognise hand gestures using Deep Learning Algorithms.
