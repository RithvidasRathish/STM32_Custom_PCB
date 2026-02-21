# Custom STM32 Automotive Control PCB

A custom-designed 4-layer STM32-based embedded control board developed for automotive and motion-control applications.  
The board integrates motor driving, CAN communication, and motion sensing in a compact and robust architecture.

---

## 🚀 Overview

This PCB is designed as a modular embedded control platform capable of:

- Independent control of two DC motors
- Automotive CAN network communication
- Real-time motion and orientation sensing
- Multi-voltage power management
- EMI-aware hardware design

---

## 🛠 Key Features

### 🔹 Motor Control
- Two MOSFET-based power stages for independent DC motor control
- Series current-sense resistors for motor current monitoring

### 🔹 Communication
- Integrated CAN transceiver (**NXP TJA1051**) for reliable CAN bus communication
- Suitable for automotive module integration

### 🔹 Motion Sensing
- 6-axis IMU (**MPU6050**) for acceleration and angular velocity measurement
- 3-axis magnetometer (**LIS3**) for heading and orientation detection
- Enables full 9-DOF motion tracking

### 🔹 Power Architecture
- Separate power domains: **12V / 5V / 3.3V**
- LDO regulation from 5V to 3.3V for digital circuitry
- Careful power partitioning to reduce EMI and crosstalk
- Bulk capacitors at power input
- Local decoupling capacitors at IC power pins
- Ferrite beads for power-line noise suppression

### 🔹 PCB Design
- 4-layer stack-up with dedicated continuous ground plane
- Controlled routing strategy for signal integrity
- Increased trace clearances for improved EMI performance

### 🔹 Debug & Expansion
- GPIO breakout headers for external module integration
- LED indicators for system status and debugging

---

## 🧠 Design Highlights

- Automotive-oriented hardware architecture
- EMI-aware layout and grounding strategy
- Modular design suitable for firmware experimentation and expansion
- Supports CAN-based distributed control systems

---

## 📦 Applications

- Automotive control modules
- Robotics motion platforms
- Dual-motor embedded systems
- Sensor fusion experiments
- CAN-based distributed networks

---

## 📸 Images


<img width="1205" height="798" alt="PCB_Schematics" src="https://github.com/user-attachments/assets/98fe892b-34df-40c9-972a-bcccb855818a" />
<img width="985" height="667" alt="PCB_2D_1" src="https://github.com/user-attachments/assets/d34b1a0c-6624-4377-8b38-40f56a7a0e1b" />
<img width="968" height="658" alt="PCB_2D_2" src="https://github.com/user-attachments/assets/cce82379-e49d-435d-be68-cba8f4a9e7e1" />
<img width="1080" height="744" alt="PCB_2D_3" src="https://github.com/user-attachments/assets/2b665157-0fd9-45e4-b5c1-1c3e2413a7d5" />
<img width="972" height="656" alt="PCB_3D_1" src="https://github.com/user-attachments/assets/5088f2d3-5c14-4d7b-af9a-51905b15cc89" />
<img width="839" height="517" alt="PCB_3D_2" src="https://github.com/user-attachments/assets/14ea95b2-9965-4c8b-a4ee-b6ebfc0f36ff" />


## 🧑‍💻 Author

Designed and developed by Rithvidas Rathish.
Embedded Firmware Developer  

🔗 LinkedIn:  
https://www.linkedin.com/in/rithvidas-rathish-embedded-firmware-developer/

