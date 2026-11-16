---
layout: default
title: "Project 2 Railroad Crossing"
---

# Project 2: Railroad Crossing

### In this project, I had to design a code that would manage traffic at a railroad crossing.

### The physical system should include:
  - Red LED
  - RBG LED
  - Distance Sensor
  - A gate that can lower and lift with the help of the position servo
  - Position Servo
  - A Snap! program controlling the system


## What should the system do when a train is coming?
  - Record the date, time and speed of the train when the system is activated
  - Detect the train and activate the buzzer and flashing lights
  - Lower the gate to stop traffic
  - Turn off the buzzer, light and lift the gate when the train passes

## Step 1: Recording Date, Time, and Speed
### To start off, I had to built a script that record the date, time and speed of the train when it would pass

<img width="484" height="217" alt="image" src="https://github.com/user-attachments/assets/dd9958cc-d02c-41da-80fd-c995976d8f26" />


I first had to make a variable; where the information, or the crossing record, would be stored. The green block that starts with "Crossing Record:" does just that. But the information can't be automatically filled out by itself, that's where bottom code comes to play. The bottom code joins the date, time and speed and puts it into a list. But what list does it go into? That's when I made the new list called "crossing activation," which records the crossing record every time the train passes.

  - I really struggled on this step because i mistakenly skipped the first page explaining what each block does, but after re-reading and reviewing the instructions I sorta understood that I had to make somewhere for the information to be recorded and something that get the information. I eventually asked for help because I genuinely had no idea how to start.

## Step 2: Detecting the Approaching Train
### Next, I had to build a script that would detect the train apporaching using the distance sensor.











[Finished working project video](https://drive.google.com/file/d/1gPjZw3i2FD3UsM93r2c2iyyBR-4cC1jG/view?usp=sharing)


