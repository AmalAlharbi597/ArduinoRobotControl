ArduinoRobotControl

This project is an integrated control system for DC motors using an Arduino board. This project allows you to control four motors in different directions (forward, backward, right, and left) through a simple programming interface.   It includes functions for moving the motors forward and backward, as well as alternating between directions. 



Requirements :

- Arduino Uno or any other Arduino board.
- DC motors (4 units).
- Motor driver (such as L298N).
- Connecting wires.
- Battery to power the motors.



- Motor A 
  - `enA` -> Pin 6
  - `in1` -> Pin 7
  - `in2` -> Pin 4

- Motor B: 
  - `enB` -> Pin 3
  - `in3` -> Pin 5
  - `in4` -> Pin 2

- Motor C: 
  - `enC` -> Pin 10
  - `in5` -> Pin 8
  - `in6` -> Pin 9

- Motor D: 
  - `enD` -> Pin 11
  - `in7` -> Pin 12
  - `in8` -> Pin 13

How to Use :

1. Connect the components according to the wiring diagram provided.
2. Upload the code to the Arduino board.
3. Wait for 30 seconds as the motors move forward.
4. Then, they will move backward for one minute.
5. Finally, the motors will alternate between right and left for one minute.
6. 



![Copy of L293D DC Motor Arduino (1)](https://github.com/user-attachments/assets/6045ed2c-6e65-445f-91bb-af68ce44ee98)





