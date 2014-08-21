Description
==========

This is a snake-like module robot that uses a PS2 remote to control the robot's motion and uses a android phone to perform higher computation such as computer vision and machine learning. The snake robot can be as long as you want.


This robot is design in a master-slave fashion, because we had trouble trying to talk to individual servo in a daisy chain fashion. The master module and the slave modules are arduino boards in this case we use the arduino pro mini for it's small size. The PS2 controller data is send to the master module.The master module is located in the front/head location of the snake robot that communicates to the slave modules. The master modules communicates with the slaves and sensors via the I2C interface. Each slave module performs calculations for the gait requested by the master module. 

You can find the app for android phone in the "Robot Controller" repository.

Design (In progress)
==================

The 3D prints for the master and slave modules are in the design folder. These designs were made with Autodesk 123d Designs, so please download that to view or change the design files. I have also included the STL files if youwant to directly print these out. Print these with the following settings if you are using Makerware, and it will be almost the same if your using ReplicatorG.

Infill: 100%
Number of Shells: 2
Layer Height: 0.10mm

Download Link: http://www.123dapp.com/design#download

Circuit diagrams 
================
You can find these in the circuit diagram foler. This is made with Fritzing Version 0.9.0 so download that version. 

Download Link: http://fritzing.org/download/?donation=0
