🤖 Self-Balancing Robot Using Arduino
Introduction
This project presents the development of a two-wheeled self-balancing robot built on an Arduino platform. By utilizing a PID controller and a complementary filter for sensor data fusion, the robot continuously adjusts its motor outputs to maintain vertical stability. This work explores key areas in control systems, robotics, and sensor integration, focusing on practical implementation and performance optimization.

🚀 Main Features
🔍 Sensor Fusion
Integrated an MPU6050 Inertial Measurement Unit (IMU) combining accelerometer and gyroscope sensors.

Applied a complementary filter to achieve accurate tilt angle estimation.

🎯 PID-Based Control
Manually tuned PID parameters to achieve stable and responsive balancing behavior.

🛠 Mechanical and System Modeling
Created a dynamic mathematical model of the robot.

Simulated system behavior using Simulink Simscape to estimate initial PID values.

⚡ Hardware Components
Arduino microcontroller

MPU6050 IMU sensor

GA37-520 DC geared motors

TB6612FNG dual motor driver

Li-ion rechargeable battery

Custom-designed steel and acrylic chassis

📈 Project Development Workflow
🏗 Hardware Construction
Assembled and mounted components onto a custom-fabricated chassis ensuring mechanical stability.

💻 Software Implementation
Programmed the Arduino to execute a PID control loop for balance correction.

Developed a complementary filter algorithm to fuse accelerometer and gyroscope data.

🔧 Testing and Calibration
Performed iterative tuning of the PID controller through experimental testing.

Conducted reliability tests to validate stability under different operating conditions.

✅ Results
Consistent Stability:
Successfully maintained upright balance using only tilt angle feedback.

Accurate Control:
Achieved precise and smooth motor control through PID tuning.

Robust Performance:
Demonstrated reliable operation across various surfaces and disturbances.

🔮 Future Enhancements
Enhanced Sensor Fusion:
Implement a Kalman filter for superior noise reduction and angle estimation.

Advanced Control Algorithms:
Explore adaptive control or model predictive control (MPC) for better system dynamics.

Navigation and Obstacle Avoidance:
Integrate ultrasonic sensors to enable autonomous navigation and obstacle detection capabilities.

✨ Conclusion
This project serves as a hands-on demonstration of embedded system development, real-time control strategies, and robotic balance, providing a strong foundation for future research in autonomous mobile systems.

