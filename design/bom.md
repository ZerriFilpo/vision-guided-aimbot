# Bill of Materials (BOM)

Project: Vision-Guided Mouse Robot  
Status: Hardware acquired  
Last update: 2025-12-13

This document lists the exact hardware components selected and purchased for the project.  
All items below correspond to the current implementation baseline.

---

## 1. Control and Processing

| Item | Model | Qty | Description |
|-----|------|-----|-------------|
| Microcontroller Board | STM32 Nucleo-F446RE | 1 | ARM Cortex-M4 development board used as the main embedded controller. Handles motor control, communication with host PC, and actuator control. |

---

## 2. Mobility and Motion System

| Item | Model | Qty | Description |
|-----|------|-----|-------------|
| DC Gear Motor | N20 DC Gear Motor (6V) | 4 | Miniature DC motors with integrated gearbox used for omnidirectional locomotion. |
| Motor Encoder | N20 Magnetic Encoder | 4 | Quadrature encoders mounted on the rear shaft of each motor for speed and direction feedback. |
| Motor Mount | N20 Metal Mount | 4 | Metal brackets used to mechanically secure the motors to the acrylic chassis. |
| Omnidirectional Wheel | 48mm Mecanum Wheel (3mm shaft) | 4 | Mecanum wheels enabling full 2D omnidirectional motion; includes left and right wheel variants. |
| Motor Driver | TB6612FNG Dual H-Bridge Module | 2 | Dual-channel motor drivers used to control DC motor direction and speed via PWM. |

---

## 3. Mouse Interaction Actuation

| Item | Model | Qty | Description |
|-----|------|-----|-------------|
| Servo Motor | MG90S Micro Servo (180°) | 1 | Positional micro servo used to actuate a physical mouse click mechanism. Provides controlled angular motion and sufficient torque for button actuation. |

---

## 4. Power System

| Item | Model | Qty | Description |
|-----|------|-----|-------------|
| Battery | LiPo Battery 2S 7.4V 300mAh | 1 | Primary power source supplying the system. Compact and lightweight, suitable for mobile robotic platforms. |
| Battery Charger | 2S LiPo Balance Charger | 1 | Dedicated charger for safely charging the 2S LiPo battery with cell balancing. |
| Voltage Regulator | LM2596 Step-Down Buck Converter | 1 | DC-DC buck converter used to regulate battery voltage down to a stable 5V rail for motors and servo. |
| Power Switch | SPST Toggle Switch | 1 | Master on/off switch placed between the battery and power regulation stage. |

---

## 5. Wiring and Prototyping

| Item | Model | Qty | Description |
|-----|------|-----|-------------|
| Prototyping Board | Perforated PCB (7×9 cm) | 1 | Used to mount motor drivers, voltage regulator, and power distribution wiring. |
| Jumper Wires | Dupont Wire Kit | 1 set | Assorted male/female jumper wires for signal-level connections. |
| Power Wiring | Silicone Wire 22–26 AWG | 1 set | Flexible wiring used for power distribution and motor connections. |
| Connectors | JST Connector Set | 1 set | Used for modular power and motor connections, allowing easy disassembly. |

---

## 6. Mechanical Structure

| Item | Model | Qty | Description |
|-----|------|-----|-------------|
| Chassis | Acrylic Plate (custom cut) | 1 | Main structural plate, includes central opening for mouse placement and mounting holes for motors and electronics. |
| Standoffs | M3 Spacers (10–20 mm) | 1 set | Used to elevate electronic boards above the chassis surface. |
| Fasteners | M2 / M2.5 / M3 Screws and Nuts | 1 set | Mechanical fasteners for motors, mounts, boards, and chassis assembly. |

---

## 7. Vision and Interaction

| Item | Model | Qty | Description |
|-----|------|-----|-------------|
| Camera | USB Webcam | 1 | Camera used by the host computer to capture the monitor image for visual target tracking. |
| Mouse | Standard USB Optical Mouse | 1 | Physical mouse placed within the robot chassis and manipulated by the platform. |

---

## Notes
- This BOM represents the **initial hardware baseline** for the project.
- Component substitutions may occur during integration if required by mechanical or electrical constraints.
- All modifications will be tracked and documented in subsequent revisions of this file.
