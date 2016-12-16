---
layout: project
type: project
image: images/hawk.jpg
title: QuadCopter
permalink: projects/quadcopter
date: 2016
labels:
  - C++
  - GitHub
  - Robotics
summary: An unmanned ariel system which uses opensource "ardupilot" to transfer data securely.
---

<img class="ui medium right floated rounded image" src="/images/Pixhawk-Inforgraphic2.jpg">

Aerial drones can be handy tools to have. Whether their purpose be taking that perfect in-air shot for a wedding, transporting goods, or monitoring hazardous environments; drones are quickly becoming tech favorites among owners. However, there is one big issue drone owners are rapidly becoming familiar with.. drone hijacking! In most conventional drones, there is simply no protection against signal interception and man-in-the-middle attacks. My project aims to remedy this problem. This project aims to modify a popular communications protocol, MAVLink, to use encryption algorithms in order to secure the link between a UAV and controller. 

For this project my team used [Ardupilot](https://github.com/ArduPilot/ardupilot) open-source software in combination with a [pixhawk](https://pixhawk.org/) open-hardware unit to simulate a typical flight. Currently, we are working on implementing the encryption algorithms to secure communication with the pixhawk. 

This is an ongoing project, and while incomplete, the progress I have made so far in getting the controller and the pixhawk to communicate is nothing to be ashamed of. Through this project, I gained proficiency operating in a Linux environment, experience working with real-time operating systems, proficiency with git, and of course, I learned about data encryption. 
