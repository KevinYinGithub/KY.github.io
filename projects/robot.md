---
layout: default
title: Celebi
permalink: /projects/robot/
---

# Celebi
<!-- Project demo video -->
<video controls style="width:100%; max-width:600px; border-radius:8px; margin-top:15px;">
  <source src="{{ '/images/IMG_2511.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Overview
Our team built a custom-built robot called Celebi, engineered to complete in robowrestling tournaments. The robot was designed and programmed in C++ to detect opponents, react quickly, and push the opponent out of the small sumo ring. 

I was tasked designing the robot's control algorithm and debugging the robot for any unexpected behaviors during testing. One of my key contribution is designing an algorithm simply called "circle", where if the sensors could not detect the opponents robot for a microsecond, it will try to go around the edge of the sumo ring for period of time, increasing its chance of re-engaging with the opponent's robot. Additionally, I helped debug the robot for any undefined behavior, improving the robot reaction by 40% and ensuring reliable behavior.

## Technical Details
- Use C++ to implement the robot's behaviors and control logic.
- Teensy 4.1 microcontroller was used to act as the robot's brain, handling sensor input, motor control, and decision making.
- Integrated world state tracking to monitor the robot's position, opponent's position, and a timer for action execution.
- Implemented a robot action module to control the left and right motor within function like "drive_forward" or "brake".

## What I Learned
- Gained strong proficiency in C++ programming.
- Learned to design algorithms for automated decision making, which builds critical thinking skills applicable to cybersecurity tasks.
- Improve problem solving and debugging skills, which can be transfer to analyzing and mitigating security vulnerabilities in software system.


<a href="{{ '/projects.html' | relative_url }}" class="project-button">Back to Projects</a>
















