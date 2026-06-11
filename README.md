Animatronic Eye System 👁️👁️

This is a robotic eye setup that moves and reacts to what it sees using a camera and a set of servos. The idea is to make it feel a bit “alive” just through motion — like it’s actually paying attention instead of being a static build.

Built with an ESP32-CAM and 6 MG90S servos. 
AI was used in this project to write codes!!!

⸻

What this does

This system behaves like a robotic eye that responds to visual input.

It:

1. Captures video using the ESP32-CAM
2. Detects basic changes in the frame (motion or shifts)
3. Moves the eyes and eyelids using servos based on that input

The goal is realistic movement through simple vision-based control.

⸻

Parts used

1. ESP32-CAM (OV3660)
2. PCA Servo Driver
3. 6× MG90S Servos
4. 18650 batteries
5. Screws

⸻

How it works

1. ESP32-CAM captures frames continuously
2. Basic logic analyzes changes in the image (motion or shift detection)
3. Movement commands are sent to the PCA9685
4. The PCA9685 drives 6 servos:
    1. Left/right eye movement
    2. Up/down eye movement
    3. Eyelid motion for blinking and expression

Servos are powered separately to avoid voltage drops and instability.

⸻

Made by

Harshil