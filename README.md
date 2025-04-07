# LoRaCare – LoRa-Based Patient Health Alert System

LoRaCare is a reliable, long-range wireless health alert system designed for hospitals or home care. It ensures that patients can notify nearby medical staff even when they are far apart within a building or remote healthcare zone. Built using LoRa technology, it works without Wi-Fi or cellular networks.

---

## Features

- Instant alert button for patients
- Long-range wireless communication using LoRa
- Real-time notification to nurses/medical staff
- Compact and low-power embedded design
- Suitable for rural clinics and remote healthcare centers

---

## Hardware Used

- *LoRa Module (SX1278 / Ra-02)*
- *Arduino Nano / ATmega328P*
- *Push Button Module*
- *Buzzer or LED for alert notification*
- *Battery module or USB power*

---

## How It Works

1. *Patient Unit*: A button press on the transmitter sends a signal via LoRa.
2. *Nurse Unit*: Receives the signal and triggers a buzzer/LED to alert medical staff.
3. The system is highly efficient for use in multi-room hospitals or isolated clinics.

---

## Circuit Overview

*Transmitter Side (Patient):*
- Push Button → Arduino → LoRa Transmit

*Receiver Side (Nurse/Doctor):*
- LoRa Receive → Arduino → Buzzer/LED

---

## Getting Started

1. Upload the LoRa_Transmitter.ino and LoRa_Receiver.ino to the respective Arduino boards.
2. Ensure both LoRa modules are on the same frequency and spreading factor.
3. Power both devices and test by pressing the button on the transmitter side.

---

## Future Improvements

- Add heart rate or temperature sensors for real-time health monitoring.
- Integrate with Blynk/IoT dashboard for cloud alerts.
- Add wearable version for patient comfort.

---

## License

This project is open-source and free to use under the MIT License.

---

> *Created by [Sam](https://github.com/iamSam-dev)*  
> For smart healthcare using embedded IoT systems.
