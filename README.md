# Numato 32 Channel Ethernet Relay Board Communication using LabVIEW

## Project Description

This project demonstrates communication with the Numato 32 Channel Ethernet Relay Board using LabVIEW through both:

- Serial COM Communication
- Ethernet VISA TCP/IP Communication

The project is developed for industrial automation, relay control, hardware communication, and LabVIEW VISA communication learning purposes.

The system performs:

- Serial communication using NI VISA
- Ethernet communication using VISA TCP/IP
- Authentication disable through serial commands
- Board reboot/reset operation
- Relay ON/OFF control
- Relay status monitoring
- TCP/IP socket communication
- Remote relay operation

The project uses LabVIEW 2018 and NI VISA for communication between the PC and the Numato relay board.

---

# Hardware Used

- Numato 32 Channel Ethernet Relay Board
- Windows PC/Laptop
- Ethernet Cable
- USB Cable

---

# Software Used

| Software | Version |
|---|---|
| LabVIEW | 2018 or later |
| NI VISA | Installed |
| Windows OS | Windows 10/11 |

---

# Project Files

| File Name | Description |
|---|---|
| `RESETnumato board coomunication.vi` | Serial communication VI used to disable authentication and reboot board |
| `com1.vi` | Ethernet VISA communication VI used for relay read/write operations |
| `Screen Recording 2026-05-21 115034.mp4` | Serial communication demonstration video |
| `Screen Recording 2026-05-21 120655.mp4` | Ethernet VISA communication demonstration video |
| `README.md` | Project documentation |
