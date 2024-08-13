# Uni-Propeller-Drone

System Overview
Building a uni-propeller drone with an Arduino and a servo-based gimbal for motor thrust vectoring. This type of drone uses a single motor and propeller for lift, with servos to control the thrust direction, allowing it to manoeuvre. Below is a list of components you'll need for this project:
Microcontroller:
Atmega328p: This will serve as the brain of the drone, handling sensor inputs, controlling the servos, and regulating the motor speed.
Motor and Propeller:
Brushless DC Motor (BLDC): A high-thrust motor designed for drone applications. Ensure that the motor can generate enough thrust to lift the drone.
Propeller: A compatible propeller designed to match the motor’s specifications. Typically, for a single-propeller drone, a large propeller (e.g., 10-inch to 12-inch diameter) is used to maximize lift.
Electronic Speed Controller (ESC):
ESC: Controls the speed of the brushless motor based on signals from the Arduino. Ensure it can handle the current and voltage requirements of the motor.
Power Supply:
LiPo Battery: A lightweight, high-capacity battery that can supply enough current for the motor and electronics. Commonly, 3S (11.1V) or 4S (14.8V) LiPo batteries are used in drones.
Power Distribution Board (optional): If you have multiple electronic components, a power distribution board can help manage power delivery.
Thrust Vectoring System (Gimbal):
Servos: Two or three high-torque servos (e.g., MG90S or similar) to tilt the motor mount in different directions for thrust vectoring. This will allow you to control pitch, roll, and yaw by adjusting the direction of the thrust.
Gimbal Mount: A custom or pre-made gimbal frame that allows the motor to tilt in different directions. This can be 3D printed or constructed from lightweight materials like aluminum or carbon fiber.
Flight Control Sensors:
MPU6050: A 6-axis gyroscope and accelerometer to provide orientation and motion data to the Arduino for stabilization.
Barometer (e.g., BMP180/BMP280): For altitude sensing (optional, but useful for altitude hold).
Magnetometer (e.g., HMC5883L): For heading and orientation (optional, used for more accurate yaw control).
Frame: (Not included in the scope of this document.)
Drone Frame: A lightweight frame to hold all the components together. It can be custom-built or sourced from a commercial frame kit.
Motor Mount: A sturdy mount to hold the motor at the center of the frame and allow for gimbal movement.
Remote Control (RC) System: (Not included in this as well.)
RC Transmitter and Receiver: A 4-channel or more RC system to control throttle, pitch, roll, and yaw. Channels will be mapped to motor speed and servo positions.
