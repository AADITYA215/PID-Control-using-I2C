# PID-Control-using-I2C
PSU ECE ESD Project 2 Repository
In this project you will gain practical experience working with FreeRTOS and interfacing to an external sensor. Project #2 uses a MicroBlaze AXI based system which includes an AXI I2C IP.
The AXI I2C module is used to get gyroscope measurements from an MPU-6050 sensor.
Functionally, Project #2 implements firmware using FreeRTOS on a Microblaze-based system to measure the ROLL of an MPU-6050 Accelerometer/Gyroscope module. The angle reported by the sensor should match the target angle given to the application by the user. 
A closed-loop PID controller guides you in how much more you need to rotate the MPU-6050 to reach the target angle. Follow the given angle recommendation and try to match it over time. Capture all the angles and generate a graph.
Try to get the best suggestions by tuning the Kp (proportional), Ki(integral),and Kd (differential) gain parameters in the PID loop.
