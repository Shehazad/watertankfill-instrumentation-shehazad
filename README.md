# watertankfill-instrumentation-shehazad
# Automatic Tank Filling System – Wonderware Simulation
# Automatic Tank Filling System – Wonderware Simulation
![filling](https://github.com/user-attachments/assets/851059fe-8143-4ba0-a53a-41c51f4109b2)


## Project Overview
This project demonstrates a **fully automated tank filling system** using **Wonderware SCADA** simulation. It simulates real-time monitoring and control of a tank level using industrial instrumentation principles. The system automatically fills a tank when the level is below the setpoint and stops filling when it reaches the desired level, ensuring safe and efficient operation.

---

## Features
- Automatic start/stop of filling based on **tank level sensor readings**.
- Simulation of **Level Transmitters (LT)** and **Control Valves (CV)**.
- Real-time monitoring of tank level using **Wonderware HMI**.
- Alarm indication when tank reaches **high level or low level thresholds**.
- Easy to customize setpoints and fill rates.

---

## Components Used
- **Sensors:** Level Transmitter (LT)
- **Actuators:** Control Valve (CV), Pump
- **PLC/SCADA:** Wonderware InTouch HMI
- **Signals:** Analog (4–20 mA) for level measurement, Digital for pump/valve control

---

## How It Works
1. The level transmitter continuously measures the water level in the tank.
2. When the level drops below the minimum setpoint, the pump automatically starts, opening the control valve.
3. The tank fills until the level reaches the maximum setpoint.
4. Once the maximum level is reached, the pump stops and the valve closes.
5. HMI displays tank level, pump status, v

