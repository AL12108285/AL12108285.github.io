---
layout: default
title: "Project 1: EMS Station"
---

 # Project 1: EMS Station

### The physical system should include:
  - A traffic light
  - Red, Yellow, Green LED
  - An EMS station
  - A garage door that can physically open and close with the help of a position servo
  - A sound sensor
  - A light sensor
  - A hummingbird robotics controller
  - A Snap! program controlling the system

### When an emergency occurs, the system should:
  - Detect the emergency/siren
  - Change the traffic light sequence to safely stop traffic
  - Open the EMS garage door
  - Allow the emergency vehicle to leave
  - Detect when the vehicle has passed the Light sensor
  - Close the garage door
  - Return the traffic light to normal flashing-light operation

## What problem was I trying to solve?
### An EMS Station is located on a busy highway, and when the EMS staff needs to respond to an emergency call, they must stop the traffic in both directions to safely exit the station.

In this activity, when an emergency call comes into the station, an alarm activates. This will give the signal for the garage door to open and allow the vehicle to exit. While the vehicle leaves, a sensor tells the flashing yellow light to stay continuously yellow and after 2 seconds, it would turn red, which after the vehicle leaves the sensor would close the garage door.

### 'You will build a system that takes an incoming call from Alonzo to the EMS station. When the call is received, Alonzo’s costume will change according to the emergency and activate the siren. After the call is detected, your system will control the garage door and stop traffic in each direction in front of the EMS Station.'

## Step 1: Staying on the Stage
### To begin, I had to build a script that would allow me to move Alonzo (yellow pointy-looking guy) by clicking on it with my mouse and making him stay on the stage.

<img width="1164" height="410" alt="download" src="https://github.com/user-attachments/assets/2378d16c-a85d-4204-917e-1a02ab090549" />
 
The code circled above allowed me to move Alonzo freely while he still stayed on the stage. In other words, he would stop moving when my mouse would go off-stage. This step was probably the easiest because the code was already given to me and all I had to do was put the "if on edge, bounce" block.

 - 

## Step 2: Changing Costumes
### Next, I had to build a script that would allow Alonzo to change costumes (appearance) whenever he would touch another sprite when an emergency was happening. In this case, the Medical, Fire, and Tree sprite would change Alonzo's Costume.

<img width="1154" height="375" alt="download" src="https://github.com/user-attachments/assets/12fedad0-c76f-4d3c-9640-5e06a8306f5f" />
















