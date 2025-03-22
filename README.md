# Transparent OLED Bow Sight Display
This project is a real-time, embedded display system designed for an archery training aid using a transparent OLED screen, Raspberry Pi Pico, and an onboard IMU. The system visually assists archers by showing dynamic targeting graphics, real-time orientation feedback, and trajectory predictions. It uses SPI to communicate with the OLED and I2C to interface with the BNO055 IMU, delivering a clean, heads-up display experience directly on the bow sight.

The user interface renders crosshairs, directional arrows, angle indicators, and battery percentage, while also responding to physical button inputs to toggle settings, calibrate targets, and adjust firing predictions. This embedded display enhances training by providing live aiming feedback based on arm position and angle.

This was a team project and my contribution focused on developing and optimizing the display firmware. I implemented the UI logic, bitmap rendering, and real-time sensor visualization using Adafruit’s graphics libraries, ensuring smooth updates and clear feedback for users. Apart from this I also created a case for the battery and the PCB which attached to the bow using TinkerCad, and also helped in PCB design.


