# Dispenser-Beras-Cerdas
Project for microcontrollers, controls systems, and electric motor.

This prototype is designed to precisely measure rice input using an HX711 load cell sensor and ESP32 as its core microcontroller. To enhance safety, an infrared sensor is integrated to detect the presence of a container, preventing spills during the dispensing process. Beyond the LCD user interface, the system also supports web-based monitoring and control, enabling seamless interaction via devices connected to the same WiFi network.

Additionally, this technology has potential applications in automated pet feeding systems, allowing remote control and scheduling through ESP32 as the receiver and controller.

![image](https://github.com/user-attachments/assets/63af28ad-4c32-49d8-a856-1a5abe5feed9)

At this stage, the most challenging aspect is sensor calibration, particularly for the HX711 load cell, to ensure accurate weight measurements. This process involves applying the calibration formula:
Actual Weight = (Raw Reading − Offset) × Scale Factor

where:
Raw Reading is the sensor output,
Offset is the baseline reading with no load,
Scale Factor is determined through calibration with a known weight.

Additionally, components such as servo motors are highly susceptible to damage and malfunction due to their role in supporting the opening and closing mechanism for the rice dispenser. Continuous operation under mechanical stress increases the likelihood of wear and tear.

Moreover, as beginners in web app development, we face challenges in integrating the web UI with real-time data from the microcontroller, ensuring seamless and responsive interaction between the system's hardware and software components.
