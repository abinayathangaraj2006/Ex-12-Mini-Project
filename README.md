# Ex-12 Mini Project


## ABSTRACT

Automatic plant irrigation is an important application in agriculture and gardening that helps provide the required amount of water to plants while reducing water wastage. This project presents the design and implementation of an Arduino-based automatic plant irrigation system using a soil moisture sensor and a water pump. 
The soil moisture sensor continuously detects the moisture level present in the soil and sends the sensor value to the Arduino microcontroller. The Arduino processes the sensor data and determines whether the soil is dry or sufficiently moist. When the soil becomes dry, the Arduino automatically activates the water pump through a relay module to supply water to the plant.
When the required moisture level is reached, the pump is automatically switched OFF. This system reduces the need for manual watering and ensures efficient water usage. The project demonstrates the integration of sensors, Arduino, relay control, and a water pump to create a simple, reliable, and cost-effective automatic irrigation system suitable for home gardens, agricultural fields, nurseries, and educational applications.

## CHAPTER 1 – INTRODUCTION

Automatic plant irrigation is a system designed to provide water to plants automatically based on the moisture level of the soil. Manual watering requires regular attention and may result in overwatering or underwatering. To overcome these problems, an automatic irrigation system can be used.
In this project, an Arduino UNO is used as the main controller.
A soil moisture sensor is used to detect the moisture content of the soil. When the soil becomes dry, the sensor sends a signal to the Arduino. The Arduino then activates the water pump through a relay module to supply water to the plant. When the soil reaches the required moisture level, the Arduino switches the pump OFF automatically.
This system helps reduce water wastage, saves time, and provides proper water supply to plants. It is a simple, low-cost, and efficient solution for home gardens, small agricultural areas, and plant nurseries.

## Objectives
The main objectives of the Automatic Plant Irrigation System are:

- To automatically detect the moisture level of the soil.
- To supply water to the plant when the soil becomes dry.
- To automatically switch OFF the water pump when sufficient moisture is detected.
- To reduce water wastage and manual effort.
- To develop a simple and low-cost irrigation system using Arduino.


## CHAPTER 2 – LITERATURE SURVEY

Automatic irrigation systems have been developed to reduce manual effort and improve the efficient use of water in agriculture and gardening. Traditional irrigation methods require regular monitoring and may lead to overwatering or water wastage.
Recent irrigation systems use soil moisture sensors to measure the moisture content of the soil. Microcontrollers such as Arduino can process the sensor readings and control a water pump automatically. When the soil becomes dry, the pump is switched ON, and when sufficient moisture is available, the pump is switched OFF.
Arduino-based irrigation systems are widely used because they are simple, low-cost, and easy to program. These systems can be useful for home gardens, plant nurseries, small farms, and educational applications. The use of automatic moisture-based control helps provide water according to the plant's requirement and reduces unnecessary water consumption.

## CHAPTER 3 – PROPOSED METHODOLOGY

The proposed system consists of the following main components:
- Arduino UNO
- Soil Moisture Sensor
- Relay Module
- Water Pump
- Water Tank
- Jumper Wires
- Power Supply



## CHAPTER 4 – HARDWARE DESCRIPTION

## ARDUINO UNO

Arduino UNO is a popular microcontroller board based on the ATmega328P. It is widely used in embedded system and automation projects because it is simple to program and provides digital and analog input/output pins. In the automatic plant irrigation system, the Arduino UNO receives the moisture value from the soil moisture sensor, processes the information, and controls the water pump through a relay module.

### Features:

* Arduino UNO Microcontroller
* ATmega328P processor
* 14 Digital I/O pins
* 6 Analog input pins
* USB connectivity
* Easy programming using Arduino IDE
* Low-cost and low-power operation

The Arduino UNO acts as the main controller of the automatic irrigation system. It continuously reads the soil moisture sensor value and decides whether the water pump should be switched ON or OFF.

<img width="750" height="500" alt="image" src="https://github.com/user-attachments/assets/f6261fcc-529e-4a9d-9f30-085db699d55e" />


## SOIL MOISTURE SENSOR

The soil moisture sensor is used to detect the moisture content present in the soil. It provides an electrical signal based on the moisture level, which is read by the Arduino through its analog input.

The sensor helps determine whether the soil is dry or sufficiently moist. When the soil becomes dry, the Arduino activates the water pump to supply water to the plant.
