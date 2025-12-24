# ESPHome-Projection-Clock
I built a day/night projection clock built on an ESP32 with ESPHome. The projector is lit by a high-power LED driven by a constant-current board controlled with a PWM signal from the ESP32. The light is directed through a collimator, a color TFT display, and a focusing lens

I can project Time, temperature, sunrise data onto a ~12in image onto the ceiling ~70 in away. LED brightness is exposed and controlled through Home Assistant. The entire apparatus runs off of the ESP32 usb-c port at just under a 1A at full brightness.

This repository documents the design, 3d printing, and YAML code used to build the clock.

<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/7b72cab6-f9d3-44fe-ab53-76df70e6ad4c" />

