Obstacle Avoiding Robot using Arduino UNO and L298N Motor Driver

This project is an autonomous obstacle avoiding robot built with Arduino UNO, L298N motor driver, DC motors, and an ultrasonic sensor. The robot detects obstacles in its path and automatically changes direction to avoid collisions.


Components Used
- Arduino UNO  
- L298N Motor Driver Module  
- HC-SR04 Ultrasonic Sensor  
- DC Motors with Wheels (x4)  
- Servo Motor (optional for sensor rotation)  
- Lithium ion Battery Pack   
- Switch & Connecting Wires  


Working Principle
1. The ultrasonic sensor measures the distance of obstacles.  
2. Arduino processes the distance data.  
3. If the obstacle is too close, Arduino signals the L298N motor driver.  
4. The motor driver changes the robot’s direction to avoid collision.  

How to Run
1. Assemble the circuit as per the provided diagram.  
2. Upload the Arduino code to the UNO board.  
3. Power the robot using the 18650 battery pack.  
4. Place the robot in a test area and watch it avoid obstacles.  

Future Improvements
- Add Bluetooth module for manual control.  
- Use multiple sensors for 360° obstacle detection.  
- Implement AI-based navigation.  

License
This project is open-source and free to use for learning and educational purposes.
