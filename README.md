🚦 ESP32 IR Infrared Obstacle Avoidance Sensor Project
This project demonstrates how to interface an IR Infrared Obstacle Avoidance Sensor with an ESP32 microcontroller for robust object detection in robotics and automation applications. The sensor works by emitting IR light and measuring its reflection, allowing the ESP32 to identify obstacles in its path and perform intelligent actions accordingly.

🔎 Key Features
Reliable Detection: Uses digital HIGH/LOW signals to quickly determine the presence or absence of obstacles.

Adjustable Range: Integrated potentiometer for fine-tuning sensor sensitivity and detection distance.

Stable Signal Processing: Implements software debounce techniques to minimize false triggers and noise from rapid or unstable signals.

Serial Feedback: Display real-time detection status (“Obstacle Detected” or “No Obstacle”) via the Serial Monitor for ease of debugging and demonstration.

🛠️ Typical Applications
Autonomous robots and smart vehicles

Industrial automation and safety barriers

IoT devices requiring proximity awareness

Interactive games, object counters, and lab projects

🏗️ Hardware Requirements
ESP32 development board

Infrared obstacle avoidance sensor module (e.g., FC-51)

Jumper wires and breadboard (for prototyping)

Optional: buzzer, LEDs, or actuators for additional feedback

⚙️ How It Works
The ESP32 reads the sensor output using a designated GPIO pin. When an obstacle is present, the sensor outputs a LOW signal, prompting the ESP32 to take action (such as stopping motors, activating a buzzer, or logging an event). When the area ahead is clear, a HIGH signal is received. The project may include signal debouncing via software, ensuring only stable signal changes are recognized, improving the system’s reliability and accuracy.

📝 Customization & Extensions
You can easily extend this project to support:

Multiple sensors for 360° environmental awareness

Automated motor control, alarm triggering, or cloud logging

Integration with other communication protocols (Wi-Fi/Bluetooth)

Real-time dashboard visualization using web interfaces
