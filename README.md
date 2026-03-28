# 👁️ Animatronic Eye System with AI

An AI-powered animatronic eye system that can see, listen, and speak — built using an ESP32-CAM, Google APIs, and 6 MG90S servos for realistic eye movement.

---

## 🧠 How It Works

The system uses an **ESP32-CAM (OV3660)** as the brain and camera. It captures video, processes voice input via **Google Speech-to-Text**, generates intelligent responses using **Google Gemini 1.5 Flash**, and speaks back using **Google Text-to-Speech**.

The eyes move realistically using **6 MG90S servos** controlled by a **PCA9685 PWM driver** — covering horizontal, vertical, and eyelid movement for both eyes.

The result is an animatronic eye that can hold a basic AI-powered conversation while physically reacting with lifelike eye movements.

---

## 🔧 Components

| Component | Quantity | Purpose |
|---|---|---|
| ESP32-CAM (OV3660) | 1 | Brain + Camera |
| PCA9685 PWM Servo Driver | 1 | Controls all 6 servos |
| MG90S Servo Motor | 6 | Eye movement (X, Y, eyelids) |
| Jumper Wires | Many | Connections |
| Breadboard | 1 | Prototyping |

**APIs Used:**
- Google Gemini 1.5 Flash — AI responses
- Google Speech-to-Text — Voice input
- Google Text-to-Speech — Voice output

---

## 🔌 Wiring

A full wiring diagram is included in the `/wiring` folder of this repo.

The ESP32-CAM communicates with the PCA9685 over **I2C (SDA/SCL)**. The PCA9685 drives all 6 MG90S servos on separate PWM channels. Power is supplied via a regulated 5V source to avoid brownouts from servo load.

---

## 🚧 Status

Currently in progress — components acquired, wiring and firmware in development.

---

## 👤 Author

Built by Harshil — [Tech Paisa India](https://techpaisaindia.blogspot.com)
