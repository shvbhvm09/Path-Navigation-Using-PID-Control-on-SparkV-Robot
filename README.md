# Path-Navigation-Using-PID-Control-on-SparkV-Robot

## Project Overview

In this project, we developed a SparkV line follower bot equipped with IR sensors to navigate a given path within 30 seconds using PID (Proportional-Integral-Derivative) control. The objective was to implement an effective PID controller to achieve accurate path-following performance. Throughout the project, we gained valuable insights into control systems and sensor integration.

## Hardware Specifications

The bot used in this project is the SparkV robot, designed jointly by NEX Robotics and the Department of Computer Science and Engineering at IIT Bombay. Below are the key hardware specifications of the robot:

- **Microcontroller**: ATMEGA16A
- **Battery**: Rechargeable 7.2V 600mA NiMH Battery with onboard intelligent charger
- **Sensors**:
  - 3 Analog White Line Sensors
  - 3 Analog IR Proximity Sensors
  - 3 Directional Light Intensity Sensors
  - Battery Voltage Sensor
  - TSOP1738 IR Receiver (for TV remote control)
  - Position Encoders
  - Support for up to 3 MaxBotix EZ Series Ultrasonic Range Sensors
  - Support for a servo-mounted sensor pod for 180-degree scanning (map making)
- **Display and Indicators**:
  - 2x16 Alphanumeric LCD
  - Multiple LED indicators for debugging
  - Buzzer
- **Motor Control**: L293D Motor Driver
- **Speed**: 15 cm to 20 cm per second (depending on the model)

## PID Control Implementation

We implemented a PID control algorithm to manage the line-following behavior of the bot. The PID controller helps in adjusting the bot's direction and speed to stay aligned with the path, minimizing deviation.

## Lessons Learned

During this project, we learned:
- Effective implementation and tuning of PID controllers for robotic applications
- Integration of various sensors for improved accuracy and performance
- Practical aspects of real-time system control and debugging

## How to Use

1. **Setup**: Connect the SparkV bot according to the hardware specifications mentioned above.
2. **Configuration**: Ensure that the PID parameters are tuned correctly based on the path and performance requirements.
3. **Operation**: Deploy the control logic and test the bot on the designated path.

