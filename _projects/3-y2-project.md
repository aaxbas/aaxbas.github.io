---
title: "Year 2 Project - IR Based Autonomous Vehicle Tracking System"
excerpt: "Year 2 University Project<br/><img src='/images/portfolio/y2-project.jpg'>"
collection: portfolio
---

For this project we were tasked with creating an autonomous mobile robot system. We decided to develop our idea based on IR based autonomous navigation in ambulances
where, unfortunately, long response times are common. The aim of the project was to create an autonomous ambulance that can autonomously navigate towards a stretcher and place it safely atop it's bed.
We were given a small budget and a kit containing 2 Arduino Megas and some basic electronics including motors, batteries and sensors.

![](/images/portfolio/y2-forklift.gif)

## Role
I worked on developing the main control/navigation system and designing the electric circuit. The navigation system consisted of 2 IR receivers placed on the robot and 4 IR transmitters placed on the stretcher, tuned at different frequencies.
This allowed for 2D orientation tracking of the stretcher to be picked up. To safely pick up the stretcher and ensure that it is balanced appropriately, a simple proportional controller was implemented to control the amount of movement required
to rebalance the stretcher.

The circuit was designed to be modular and compact as to be easily installed into any mobile robot. It also includes the option to switch between either battery power or mains.

## Media
![](/images/portfolio/y2-flow.gif)

Main control flow

![](/images/portfolio/y2-stretcher.gif)

Stretcher IR transmitter frequencies

![](/images/portfolio/y2-circuit.png)

Circuit design
