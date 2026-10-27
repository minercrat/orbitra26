# ORBITRA '26 — MMMUT CubeSat Mission Control & Avionics

Ground Station and Avionics firmware developed for **ORBITRA'26**, organized by the **Drone & IoT Club, Madan Mohan Malaviya University of Technology (MMMUT)** in association with **Antariksh Prayogshala**.

## 🛰️ Live Mission Control Dashboard
Access our Ground Station online: [https://minercrat.github.io/orbitra26/](https://minercrat.github.io/orbitra26/)

## 🛠️ Hardware Kit & Avionics
- **Microcontrollers:** 2x ESP32 Dual-Core (CubeSat Tx & Ground Rx via 2.4 GHz ESP-NOW)
- **Avionics & IMU:** MPU6050 (6-DOF Accelerometer & Gyroscope over I2C)
- **Altimeter & Environment:** BMP280 (Barometer) + DHT11 (Chassis Temp & Humidity)
- **Navigation:** NEO-6M GPS with ceramic patch antenna (UART @ 9600 baud)
- **Power Subsystem (EPS):** 2S Li-Ion Battery (7.4V) with 2S BMS & LM2596 Buck Step-Down to 5.0V

## 📂 Project Structure
- `/index.html`: Mission Control Ground Station with 3D Attitude visualizer, PFD, and GPS tracking.
- `/firmware/`: ESP-NOW transmitter & receiver Arduino sketches.
- `/cad/`: STL models for 3D printed 1U CubeSat chassis.
- `/schematics/`: Wiring and power distribution diagrams.
- `/docs/`: Pre-flight checklist & Viva preparation guide.
