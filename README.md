# Smart_Baby_Room_with_IOT
  Smart Baby Room with IOT | Arduino Mega , Arduino Uno , ESP32 , C++ , Sensors

The Smart Baby Room with IoT project integrates multiple IoT devices to enhance the comfort and safety of a baby's room through automation and smart technology. This project includes four primary functions:

## Key Functions

###Cry Detection and Cradle Automation
- **Input:** Positive sensor reading from Voice Sound Detection Mic sensor.
- **Process:** Sending output signal to servo motor pin.
- **Output:** Swing the cradle.
- **Definition:** The Voice Sound Detection Mic sensor detects sound levels and triggers the cradle's movement.

###Smart Lighting System
- **Input:** WIFI signal.
- **Process:** Sending WIFI signal through ESP32S board.
- **Output:** Turn the room light on.
- **Definition:** The ESP32S WIFI Bluetooth board facilitates wireless communication to control the lighting.

###Door Control System
- **Input:** Positive reading from RFID Module and RFID key tag token.
- **Process:** Sending output signal to servo motor pin.
- **Output:** Open the door.
- **Definition:** The RFID Module kit is used for secure and automated door access.

###Temperature Regulation
- **Input:** Positive reading from DHT11 Temperature and Humidity Sensor.
- **Process:** Sending output signal to the fan.
- **Output:** Activate fan.
- **Definition:** The DHT11 sensor monitors and maintains optimal temperature and humidity levels.

This project demonstrates a comprehensive approach to creating a smart environment for infants, leveraging IoT technologies for automation, safety, and convenience. By utilizing sensors, microcontrollers, and wireless communication, the Smart Baby Room ensures that the baby’s needs are met efficiently and automatically.

  
