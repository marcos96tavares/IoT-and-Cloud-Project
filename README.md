# 🏠 Smart Home IoT System – CS5053 Coursework

This repository contains the **Smart Home IoT Simulation** project developed for the **Cloud Computing and the Internet of Things** module (CS5053). The project demonstrates the integration and automation of various IoT devices within a simulated home environment using **Cisco Packet Tracer**.

---

## 📌 Overview

The aim of this project is to design and simulate a smart home using IoT technology. The system includes sensors, actuators, gateways, and a central server to manage data and behavior in real time. Through this setup, users can remotely monitor, control, and respond to environmental events such as temperature changes, gas leaks, humidity, and motion detection.

---

## 🛠️ Technologies Used

- **Cisco Packet Tracer** – for IoT device simulation and network topology
- **Microcontroller Programming (MCU-PT)** – using Python
- **IoT Services** – via Packet Tracer's built-in IoT server
- **LAN Configuration** – using routers, switches, and IP addressing

---

## 🧩 Key Components

| Device            | Description                                 |
|-------------------|---------------------------------------------|
| Router & Switch   | Network routing and interconnectivity       |
| Home Gateway      | Central IoT controller                      |
| Registration Server | Stores and validates IoT device data     |
| MCU-PT            | Microcontroller for sensor logic            |
| Sensors           | CO/CO2, Trip, Temperature, Water level      |
| Actuators         | Sprinkler, Fan, Heater, Garage Door         |
| LCD Display       | Real-time data display                      |
| End-User Devices  | Laptops, Tablets, PCs, Smartphones          |

> The full list includes 30+ components configured with wired/wireless connections.

---

## 🌐 Network Architecture

- LAN and WAN configuration using static IPs
- Server IP: `192.168.0.20`
- Router interfaces:  
  - To Server: `192.168.0.1`  
  - To Home Gateway & PC: `192.168.1.1`
- Home Gateway IP: `192.168.1.3`
- All IoT devices are connected to the Home Gateway

---

## 🔄 Configuration Highlights

- Manual setup of IPs for all network devices
- Username/password setup for IoT server access
- IoT device configuration through Packet Tracer interface
- Python scripting for LED blinking on MCU-PT

---

## 🔬 Simulated Scenarios

| Scenario | Description |
|----------|-------------|
| **S1** | Monitor & control devices from PC/tablet dashboard |
| **S2** | Sprinkler + Water Sensor → LCD triggers when > 5cm |
| **S3** | Wind Turbine power output monitored via laptop |
| **S4** | Garage door opens automatically if CO > 60% |
| **S5** | Humidity increase when humidifier is active |
| **S6** | Trip sensor triggers siren |
| **S7** | Thermostat sends heating/cooling data to MCU and Temp Sensor |

---

## ▶️ How to Run

1. Open the `.pkt` file in **Cisco Packet Tracer**
2. Configure network devices if needed using the provided IPs
3. Use end-user devices (PC, phone, tablet) to:
   - Open the **IoT Monitor** application
   - Enter gateway IP: `192.168.1.3`
   - Login with saved credentials
4. Monitor real-time data and activate sensors/actuators manually
5. Use the **MCU-PT** to trigger Python-based logic

---

## 📁 Folder Structure

