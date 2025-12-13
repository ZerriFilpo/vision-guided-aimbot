# vision-guided-aimbot

A hardware–software robotic platform that physically moves and clicks a computer mouse based on visual target tracking.

This repository contains the design, documentation, and source code for a compact omnidirectional robot inspired by real-world vision-guided systems. The platform integrates a real-time vision and tracking pipeline with an embedded motion control system to autonomously interact with a standard computer interface in the physical world.

Inspired by Kamal Carter video. 
https://www.youtube.com/watch?v=ne9bmMX82iY&t=81s

---

## Project Status (as of 2025-12-13)

- System concept and overall architecture defined
- Core hardware components selected and ordered
- Repository layout established
- Design documentation and integration planning underway

---

## Repository Structure

vision-guided-aimbot/
├─ README.md # Project overview and current status
├─ app/ # Application code (firmware and host)
│ ├─ firmware/ # Embedded C for microcontroller
│ ├─ host/ # Vision/tracking and communication
│ └─ shared/ # Cross-component definitions
├─ design/ # Design and engineering documentation
│ ├─ architecture/ # Diagrams, data flows, decisions
│ ├─ hardware/ # BOM, power tree, wiring
│ └─ mechanical/ # Chassis and mounting layouts
└─ .github/workflows/ # CI/CD workflows (future)

---

## High-Level Description

This robotic platform consists of:

- A host computer responsible for real-time processing and visual tracking of screen targets
- An embedded microcontroller receiving commands and controlling actuators
- A mobile base using omnidirectional motion hardware
- A mechanical click actuator to physically interact with a mouse
- A regulated battery system providing power to motors and control electronics

Current focus is on completing the design specification and preparing for mechanical integration. Implementation of firmware and host software will proceed once components arrive.

