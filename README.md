# 2312_BadgePlace

## Project Report 🇫🇷
You can find the full project report [here](./doc/rapport/Rendu%20final/2312_BadgePlace_RapportComplet.pdf). *(The report is written in French)*

## Project Files
- **PCB Production Files**: [here](./doc/rapport/Rendu%20final/2312_BadgePlace_Fabrication.pdf).
- **Schematics**: [here](./doc/rapport/Rendu%20final/2312_BadgePlace_Schematiques.pdf).

## Overview
This project is an **RFID Badge Access Control System** designed to restrict access to workstations based on RFID badge authorization. The system communicates with a central database via Ethernet or Wi-Fi and is managed by a PIC32 microcontroller. It includes visual and audible alerts, optimizes power consumption, enhances security, and provides usage tracking.

## Features
- **RFID Authorization**: Limits access to workstations based on authorized RFID badges.
- **Multiple Communication Options**: The system communicates with a central database over Ethernet or Wi-Fi.
- **Visual and Audible Alerts**: Provides alerts when a badge is scanned or when access is denied.
- **Power Optimization**: Designed to minimize power consumption during operation.
- **Access Levels**: Manages multiple users with different access levels.
- **Usage Tracking**: Logs the usage of the workstations for monitoring purposes.

## Components
- **Microcontroller**: PIC32 (manages communication, controls alerts, and processes RFID data).
- **RFID Module**: Reads badge data and sends it to the microcontroller for validation.
- **Communication**: Ethernet or Wi-Fi for sending data to the central database.
- **Relay Module**: Controls workstation power based on badge authorization.
- **3D Printed Case**: Custom-designed case for housing the electronics.

## How It Works
1. **RFID Badge Scanning**: Users scan their RFID badge at the workstation.
2. **Data Transmission**: The badge data is sent to the central database via Ethernet or Wi-Fi.
3. **Access Validation**: The system checks the badge against the database and determines if the user is authorized.
4. **Control of Workstation**: If the user is authorized, the relay module enables the workstation power; otherwise, access is denied.
