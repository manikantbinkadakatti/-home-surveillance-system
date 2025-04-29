# Home Surveillance System 🏡🔒

## Overview
This project presents a **smart home surveillance system** integrating modern technologies like **ESP32-CAM**, **motion detection**, **smoke detection**, **mobile alerts**, and **smart locking mechanisms**. The goal is to provide a cost-effective, compact, and user-friendly security solution that can be managed remotely.

## Features
- Motion and fire detection
- Live camera feed (ESP32-CAM)
- Door status monitoring
- Intruder alerts with buzzer & mobile notification
- Smart locking system
- Cloud-based alert integration (Blynk/Telegram)
- Offline mode & backup power

## Technologies Used
- ESP32-CAM
- PIR and Smoke Sensors
- NodeMCU or Arduino
- Blynk App (Mobile Interface)
- SolidWorks (CAD)
- Circuit Design (Fritzing / Tinkercad)

## Hardware Used
| Component | Description |
|:----------|:------------|
| ESP32-CAM | Video capture & image processing |
| PIR Sensor | Motion Detection |
| MQ-2 Sensor | Smoke/Gas Detection |
| Servo Motor | Door Lock Control |
| Buzzer | Audible alert |
| Power Supply | Battery or USB |
| Fire Sensor | Fire alarm trigger |

## How to Use
1. Flash `esp32_cam_doorlock_alert.ino` onto the ESP32-CAM.
2. Connect PIR, Smoke, and Fire sensors as per `circuit_diagram.png`.
3. Set up the mobile app (Blynk) and update credentials in code.
4. Run the system — get mobile alerts on intrusion, fire, and door status.
5. Use app interface for lock/unlock actions.

## Screenshots
> (Add images here)
- Circuit Design  
- Flowchart  
- CAD Model  
- Mobile App UI

## File Structure
home-surveillance-system/
│
├── README.md
├── report/
│   └── Home_Surveillance_System_Report.pdf
│
├── circuit/
│   └── circuit_diagram.png
│
├── cad_models/
│   ├── box.png
│   ├── door.png
│   └── full_assembly.png
│
├── docs/
│   ├── empathy_map.png
│   ├── user_stories.pdf
│   └── flowchart.png
│
├── code/
│   └── esp32_cam_doorlock_alert.ino
│
├── app/
│   └── blynk_app_screenshots/


## Future Improvements
- Integrate AI for face recognition
- Add LDR-based night vision toggle
- Add cloud video backup (Firebase, AWS)

## Authors
- Manikant Binkadakatti – Automation & Robotics, KLE Technological University

## License
This project is for academic purposes. Contact authors for reuse or collaboration.

---
📱 Stay secure. Stay smart. 🔐
