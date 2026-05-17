# Roberto Coria

**Computational Robotics Engineer | Full Stack Developer**

[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio--rcv.vercel.app-a78bfa?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-rcv.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Roberto%20Coria-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roberto-coria-vargas-088231309/)
[![Email](https://img.shields.io/badge/Email-roberto21coria02%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:roberto21coria02@gmail.com)

---

## About me

Two things guide my approach to building. In robotics, the challenge lies in making the software work within physical limitations: sensors have limits, motors have lag, and the real world doesn't behave like a simulation. This tension is what interests me most about this field, and where I want to continue progressing, toward teams that develop at the level of Boston Dynamics.

In web development, I value the opposite: the ability to transform an idea into a functional product using only code. Clean architecture, modular structure, and an interface that reflects the quality of the underlying code: that's the standard I set for myself in both areas.

**Recent graduate of the Universidad Politécnica de Yucatán (UPY).**

---

## What I'm building now

### Zero Trail — Electric Vehicle Catalog & Database

A near-complete EV catalog and comparison platform built with the MERN stack. Structured database of real vehicle data, functional search and filtering, and a UI built to match the premium context of the automotive industry. Currently resolving final bugs before public release.

**Stack:** MongoDB · Express · React · Node.js · Material-UI · REST API

[View on GitHub](https://github.com/RobertoCV10/PortfolioRCV)

---

## Featured projects

### Rocket Telemetry System

Real-time monitoring for experimental rockets

Built the full telemetry pipeline for a student rocket: sensor data acquired by an ESP32, transmitted via LoRa, and visualized on a live Python dashboard. LoRa was the natural choice — it's the de facto standard in amateur rocketry for a reason, and WiFi/Bluetooth simply don't hold up at altitude and distance.

The hardest part wasn't the transmission itself. With multiple sensors reporting simultaneously, I had to design a lightweight parsing protocol from scratch: each sensor prefixed its value with an identifier (t45 for temperature, and so on), so the receiver could reconstruct the data stream reliably without dropping or misassigning readings.

**Stack:** ESP32 · LoRa · Python · Real-time systems · Data visualization

[View on GitHub](https://github.com/RobertoCV10/Rocket-data-monitoring-interface-using-ESP32-and-LoRa-)

---

### Autonomous Cart with Robotic Arm

ROS + Raspberry Pi + Arduino control stack

Developed the complete control system for a mobile robot with an integrated arm: ROS handling navigation and coordination, Arduino managing motor output, and a Tkinter interface for manual override.

One real constraint I ran into: streaming two cameras simultaneously inside the Tkinter interface wasn't feasible without introducing lag that broke usability. Rather than force it, I wired each camera to launch in an external window triggered from the interface — functional, clean, and honest about the hardware limits.

**Stack:** ROS · Raspberry Pi 4 · Arduino · C++ · Python · Control systems

[View on GitHub](https://github.com/RobertoCV10/Robotic-cart-with-arm-using-ROS-Raspberry-PI-4-and-Arduino)

---

## Technical skills

### Languages
<div>

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

</div>

### Robotics & Embedded Systems
<div>

![ROS](https://img.shields.io/badge/ROS-0A0FF5?style=flat-square&logo=ros&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=Arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=flat-square&logo=Raspberry-Pi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

</div>

### Web — MERN Stack
<div>

![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=flat-square&logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404d59?style=flat-square&logo=express&logoColor=%2361DAFB)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=%2361DAFB)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)

</div>

### Tools & DevOps
<div>

![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-0081CB?style=flat-square&logo=mui&logoColor=white)

</div>

---

## How I debug

Most of my debugging happens at the boundary between layers — the point where hardware behavior stops matching what the software expects. That's where I'm most comfortable.

Building these projects meant I couldn't hand off a problem to "the hardware guy" or "the backend guy." When the robot's camera stream lagged, I had to figure out whether it was a USB bandwidth issue, a ROS node bottleneck, or a Tkinter rendering limit. When the rocket's data stream arrived garbled, the fix wasn't in the radio — it was in designing a parsing protocol that could survive a noisy channel.

That's the way I approach every system: understand the constraints at each layer before assuming the problem is where it first appears.

---

## Language proficiency

| Language | Proficiency | Primary use |
|----------|-------------|------------|
| Python | Advanced | Robotics, data visualization, automation |
| C++ | Advanced | Embedded systems, ROS nodes, performance-critical code |
| JavaScript | Proficient | Full-stack web development, React applications |
| HTML/CSS | Proficient | Frontend design, responsive interfaces |

**Most active in:** Python and C++ for robotics projects; JavaScript/React for web applications

---

<div align="center">

**Open to full-time roles, internships, and problems worth solving.**

</div>
