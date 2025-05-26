# Claw-Machine-2025

Claw Machine using 4 motors with 1 Arduino Uno


**0. Project Abstract**

Fully Functional Claw Machine using Gear Rack and Pinion assisted with 4x motors and 1x Arduino Uno


**1. Hardware**

![image](https://github.com/user-attachments/assets/6fba1789-37ae-40ff-80fa-24f6fac1c315)


**2. How it Works**

SVG file -> Laser Cutter Machine (material: 3mm wood)

X-Y axis is controlled with Joystick input

Z axis is controlled with switch (clockwise, counter clockwise)

Claw is controlled with Digital Push button


**3. Pinwork**

X axis: Arduino Uno D 2-5

Y axis: Arduino Uno D 6, 7

Z axis: Arduino Uno D 8, 9, 10, 11

Claw Input(Servo Motor) : Arduino Uno D 13

Joy Stick: Arduino Uno A 0, 1

Claw Switch : Arduino Uno A3

Switch 2, 3(Servo Motor): A 4 , 5 <- The pins are Analog but for Uno, it can also take Digital Input as well.


**4. Final Work**

![image](https://github.com/user-attachments/assets/0306a0bb-6f43-41e9-b0a5-a9f8dd5050e5)


![image](https://github.com/user-attachments/assets/320f6d24-65d5-4ac7-927a-5099bcfb82e3)


![image](https://github.com/user-attachments/assets/dc0d535e-0873-4199-abb3-c66167ff16b8)


**5. Ways to Improve**

X, Y axis is controlled with Joystick, and each axis are controlled with different units.

However, signal noise occurs and affect the other axis. This can be upgraded using better joy stick module.
