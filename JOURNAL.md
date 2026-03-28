# 📓 Build Journal — Animatronic Eye System

---

## Entry 1 — Project Start & Planning
**Date:** March 28, 2026
**Time Spent:** ~2 hours

### What I did:
Started planning the animatronic eye system. The goal is to build a pair of AI-powered animatronic eyes that can see, listen, think, and speak — all in real time.

Decided on the full hardware stack:
- ESP32-CAM (OV3660) as the main microcontroller and camera module
- PCA9685 PWM driver to control all 6 servos via I2C
- 6x MG90S servos for eye movement
- Google Gemini 1.5 Flash for AI responses
- Google Speech-to-Text for voice input
- Google Text-to-Speech for voice output

### Challenges I'm thinking about:
- Power management — 6 servos drawing current could cause brownouts
- Latency in the Speech → Gemini → TTS pipeline
- Mechanical design of the eye socket

### Next steps:
- Finalize wiring diagram
- Start servo firmware via PCA9685
- Test ESP32-CAM Wi-Fi + Google API connection
