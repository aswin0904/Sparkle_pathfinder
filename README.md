# Line Follower Robot

An Arduino Nano-based Line Follower Robot is utilizing a QTR-8RC sensor array and a DRV8833 motor driver. The robot has been designed for responsive and accurate line following through PID control, and comes with Bluetooth-based tuning to make real-time tuning.

---

You may be interested in:
 Features
- PID-controlled line following algorithm
- Real-time sensor data and motor speed output via Serial Monitor
- Bluetooth-based tuning of `Kp`, `Ki`, `Kd` PID constants
- Manages straight lines, smooth curves, and sharp 90° turns
- Line loss recovery logic and re-alignment

---

 ⚙️ Hardware Used
- Arduino Nano
- QTR-8RC Reflectance Sensor Array
- DRV8833 Dual Motor Driver
- N20 600 RPM Geared Motors
- HC-05 Bluetooth Module
- 7.4V Lipo Battery Pack

---

## Software Features
- PID control logic for stable and smooth movement
- Real-time Bluetooth commands for:
  - Starting/stopping the robot
  - PID constant adjustments
- Serial monitor output for debugging:
  - Sensor readings
  - Calculated position
  - Motor speeds

---

## Photos

### Top View of the Robot
![Robot Top View](/topview.jpg)

### Circuit Diagram
![Circuit Diagram](images/circuit-diagram.png)

---

##  Getting Started

1. **Upload** the Arduino code from the `src/` directory using the Arduino IDE.
2. **Connect** to the HC-05 module using a Bluetooth terminal app (e.g., Serial Bluetooth Terminal).
3. **Tune** the PID constants using the Bluetooth interface:
- `P100` to make `Kp = 100`
   - `I050` for `Ki = 50`
   - `D020` for `Kd = 20`
   - `S1` to initiate the robot, `S0` to halt

4. **Position** the robot on a white background black line and initiate the system.

---

##  Author

**Aswin Kumar A**
Second Year EEE Student, SSN College of Engineering
GitHub: [aswin0904](https://github.com/aswin0904)  
Project Year: 2025

---

Feel free to fork this repo, propose changes, or contribute!

