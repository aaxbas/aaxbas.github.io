---
title: "Project Hex - Autonomous Hexacopter"
excerpt: "Drone built to compete in the IMechE UAS Challenge<br/><img src='/images/portfolio/HEX.gif'>"
collection: projects
---

The IMechE UAS Challenge is an annual competition for the design and development of unmanned aerial systems (UAS). I worked on developing the computer vision, communications and navigation subsystems. This has given me a lot of experience in embedded systems and linux development, as well as radio communications. 

![](/images/portfolio/drone-hex.jpg)

## Tasks
The aim of the competition is to create a UAS capable of flying to a number of geographical waypoints autonomously, while delivering certain First Aid payloads safely and detecting targets along the way.
## Role
I mainly worked as a control engineer within the project to design the flight control and navigation software as well as the target detection software. The following is my contribution to the project:
* Used OpenCV, Python and tesseract OCR to design and develop a computer vision solution required to detect specific targets from a drone as part of a multi-discipline team.
* Utilized the MAVLink communication protocol, hardware (UART) and software (bit-banging) serial to send commands to and from a Pixhawk flight controller and two Raspberry Pi 3 computers.
* Designed the navigation system using a combination of the above two technologies and custom mission planning scripts written in Python.

![](/images/portfolio/CV-hex.jpg)

GitHub: [https://github.com/jnoxro/HipPy](https://github.com/jnoxro/HipPy)

In 2019, I was elected Control Team Leader, where I oversaw the development of the control system and shifted focus towards working on the communication system. My responsibilites included:
* Leading a team of multi-disciplinary engineers in designing and developing the control system used in an autonomous aircraft to compete in the IMechE UAS Challenge.
* Expanding upon previous year’s control system design, including updating hardware to match modern standards and re-writing code to increase efficiency.
* Overseeing the development of a new computer vision program in C++ and OpenCV to improve target detection speed.
* Designing an antenna tracking system with a custom PCB that increased the range of the communication system to 20 KM.

GitHub: [https://github.com/Project-Hex/HexControl1920](https://github.com/Project-Hex/HexControl1920)

## Results
### 2018-19
In the 18/19 competition entry we were able to enter the fly off event and successfully navigate towards one waypoint, before experiencing an unfortunate loss of communication due to 
radio interference, which resulted in the UAS to set off it's emergency flight termination system, where the competition guidelines stated that all motors most completely stop operating. Of course this caused the UAS to fall out of the sky and spectacularly crash into the nearby grass. Although we were disheartened, it was a very valuable learning experience and a definite area of improvement to focus on in our next entries. After all of this, we still managed to make it to 10th place in the overall rankings.

### 2019-20
Unfortunately, since the competition this season was held virtually, we were unable to test all systems in real life. However, we were able to make a test vehicle, where we tested the basic control and communication system as well as the piloted flight mode, and collected the data in order to discover areas of improvement for the design of the competition UAS. We ended up placing 4th thanks to our innovative mechanical and software design, and concept validation results from our test flight.

## Media
![](/images/portfolio/anttrack-hex.jpg)
Antenna Tracker PCB


![](/images/portfolio/hex-group.jpg)
Project Hex IMechE UAS Challenge 2019 team
