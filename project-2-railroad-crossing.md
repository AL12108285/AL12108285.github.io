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

## Step 2: Detecting Train and Stopping Traffic
### Next, I had to build a script that would detect the train approaching using the distance sensor, and add the time, date, and speed to the crossing record and stop traffic.


<img width="486" height="152" alt="72cbd626-10d6-4082-88ec-ada82fb29e6d" src="https://github.com/user-attachments/assets/3afc20a9-66b8-445d-b700-ba1c6f895fd1" />

<img width="359" height="55" alt="0f0ee61f-a12c-4709-9611-0cfaa1abc16c" src="https://github.com/user-attachments/assets/89d5fcd8-042c-4074-afb4-5c3b05e7f1cd" />

If the train passes in front of the distance sensor and the distance is below 20, this code puts the speed, time, and speed into the crossing record I made previously. It also activates the position servo to rotate 0 degrees while the train is passing and after the train is done passing, it rotates back to 90 degrees. I also added a little piece of cardboard to create the gate and stop traffic when the train is crossing.

  - This part was easy to understand after I was given the code. I, again, had no idea where to start but my friend assisted me. After reading the code multiple times, I understood what It had to do and how it did it.

## Step 3: Flashing Lights
### Furthermore, I was asked to build a script that would tell traffic when to go and when to stop to avoid accidents with the train.

<img width="471" height="440" alt="997d693e-0bf5-4979-9909-1f1232e1a53c" src="https://github.com/user-attachments/assets/bbc9a93d-454f-4514-9110-c6fa2bf994a4" />

The circled code above made my Tri-LED light flash red to signal traffic to stop while the train was passing,(with the help of the distance sensor and the code mentioned before). After the train finishes passing, the light would continuously turn green to signal that it's safe for traffic to pass.


  - This part was simple because in our last project I learned how to change the color of the light, and how to turn off and turn on the lights.




## .

[Finished working project video!](https://drive.google.com/file/d/1gPjZw3i2FD3UsM93r2c2iyyBR-4cC1jG/view?usp=sharing)

[Snap Code!](https://snap.berkeley.edu/snap/snap.html#present:Username=lvhs3&ProjectName=U2L2R%20Railroad%20Crossing)
