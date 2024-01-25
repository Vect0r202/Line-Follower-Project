# Line-Follower Robot Project

Overview
  This project showcases the design, assembly, and programming of a line-follower robot. The robot uses a set of sensors to detect and follow a predetermined path. It is an excellent example of practical robotics, combining hardware integration with software control.

Video Demonstration
  For a quick overview of the robot in action, check out our short video demonstration: https://youtube.com/shorts/CBKsZysA6GA?feature=share

Design and Assembly
  The robot's design focuses on simplicity and efficiency. Key components include a sensor array for line detection, two motors for movement, and a microcontroller for processing. The assembly process involves careful placement of these components to ensure optimal balance and sensor alignment.

Circuit Layout
  Our circuit design is straightforward yet effective. We've connected motor drivers to control the wheels, ensuring smooth and responsive movement. The sensor array is interfaced directly with the microcontroller to minimize latency in line detection.

Code Implementation
  The heart of our project lies in its code. We've used Arduino for programming the robot. Key features of our code include:

    -Sensor Calibration: Automated calibration for line detection, ensuring the robot adapts to different surfaces and line colors.
    
    -PID Control Algorithm: Implementation of Proportional-Integral-Derivative (PID) control to maintain a steady and accurate path along the line.
    
    -Motor Speed Control: Dynamic adjustment of motor speeds based on sensor input, allowing for smooth turns and straight lines.
    
    -Core Functions
    -setup(): Initializes the sensors and motors, and runs the calibration sequence.
    
    -loop(): Continuously calls pidControl() for real-time line following.
    
    -pidControl(): Implements the PID algorithm to calculate the error between the robot's position and the line, adjusting motor speeds accordingly.
    
    -setMotorSpeed(): Controls the speed and direction of each motor.
    
  Components Used
    -Arduino Microcontroller
    -L293D Motor Controller
    -QTR Sensor Array
    -DC Motors and Drivers
    -Power Supply Unit
    -Various Resistors, Cables, and Connectors

Contribution
Contributions to this project are welcome. Whether it's suggestions for code optimization, hardware improvements, or new features, feel free to fork the repository and submit your pull requests.
