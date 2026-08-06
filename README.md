Remote Sensing Blind Cane

About The Project :
A visual aid device for the visually impaired that relies on remote sensing technology using ultrasonic waves to provide the user with alerts based on obstacle distance, enabling them to detect obstacles and know their distance before collision.

Components Used :
Arduino 
Ultrasonic Distance Sensor
Audio Alert Unit (Buzzer)
Power Source

How It Works:
Pulse Emission & Reception: The ultrasonic sensor emits a high-frequency pulse. When it hits an obstacle, it reflects back and is received by the sensor.
Distance Calculation: Arduino calculates the total time and distance using the formula:

$$\text{Distance} = \frac{\text{Time} \times 0.034}{2}$$

Detection Zones: The system maps the distance into three operational zones:
Safe Zone
Warning Zone
Danger Zone

 Circuit Diagram and Simulation:

Tinkercad Simulation Link:
https://www.tinkercad.com/things/kqESg98HoY3-remote-sensing-blind-cane

 Project Files
Arduino Source Code: Remote ensing blind cane.ino
Project Documentation: Remote Sensing Blind Cane.pdf
