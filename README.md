# Ultrasonic Distance Measurement with Arduino

This project uses an **HC-SR04 Ultrasonic Sensor** interfaced with an **Arduino Uno** to measure the distance of objects in real-time. This is a foundational project for applications in **Smart Agriculture**, such as monitoring water levels in tanks or detecting obstacles for automated farm equipment.

## 🚀 Features
* Real-time distance calculation in centimeters.
* Serial Monitor output for easy debugging.
* High precision using ultrasonic sound wave reflection.

## 🛠 Components Used
* **Microcontroller:** Arduino Uno
* **Sensor:** HC-SR04 Ultrasonic Sensor
* **Others:** Breadboard, Jumper Wires

## 🔌 Pin Configuration
| HC-SR04 Pin | Arduino Pin | Description |
| :--- | :--- | :--- |
| **VCC** | 5V | Power Supply |
| **Trig** | Pin 9 | Trigger Pulse Input |
| **Echo** | Pin 10 | Echo Pulse Output |
| **GND** | GND | Ground |

## 📐 How it Works
The sensor emits an ultrasonic sound at 40,000 Hz that travels through the air. If there is an object or obstacle in its path, It will bounce back to the module. Considering the travel time and the speed of the sound, you can calculate the distance.

The formula used is:
$$\text{Distance} = \frac{\text{Time} \times 0.034}{2}$$

