# M2-embedded_Remote-Temperature-Humidity-Sensor

This project introduces a temperature and humidity monitoring/sending system, which is based on digital technology and computer technology. The system overcomes disadvantages of poor linearity, low accuracy transmission complex use of traditional system with the analog humidity sensor and makes measurement for temperature and humiture higher precision.

![temp2](https://user-images.githubusercontent.com/85119462/144152781-f234b0e2-2c0f-4113-9712-264bf0ffa7ef.jpeg)



## Folder Structure


|Folder             | Description |
|-------------------| -----------------------------------------|
| `1_Requirements`   | Documents detailing requirements and research|
| `2_Architecture`         | Documents specifying design details|
| `3_Implementation` | All code and documentation|
| `4_Test_plan`      | Documents with test plans and procedures|
| `5_Report`| Documents with report|
| `6_Images and videos`|All project related images and videos|
| `7_Other`| other related files|

# Things used in this project
# Hardware components
* Microchip Technology atmega 328p-pu
* SI7020-A20 I²C Humidity and Temperature Sensor ±4%RH ±.4°C	
* ControlEverything.com SI7020-A20 I²C Humidity and Temperature Sensor ±4%RH ±.4°C
*  433 MHz transmitter / Receiver kit
* AMS1117-ADJ voltage regulator
* Capacitor 100 µF	
* Resistor 1k ohm
* Resistor 10k ohm
* LED (generic)
* Resistor 221 ohm	
* 2AA Battery Holder for RTC	
* UDOO 2AA Battery Holder for RTC

 # Software apps and online services
* Arduino IDE	



# REQUIREMENTS    
# Introduction

Field of monitoring and remote sensing has been revolutionized by wireless sensor network . Wireless sensor networks can collect data from different sensors such as temperature, humidity, voltage, current etc. from remote locations and co-operatively pass the data through the network to the control station (or where data analysis is needed). Hence, wireless sensor networks can be used for monitoring of power data even from remote locations. Online continuous monitoring of these physical quantities from remote control station helps to co-ordinate the uninterrupted operation in the process plants, industries and even in domestic utilities . Keeping these situations in view, an attempt has beenmade in this project to monitor data through wireless sensor network for measurement of temperature and humidity .

* Sensing unit – Temperature & Humidity 
Sensor (DHT11)
* Processing unit – A Microcontroller 
(ATMEGA 328P)
* Power unit – Battery.


#  State of art/Research

![temp3](https://user-images.githubusercontent.com/85119462/144154489-56e66e2f-617c-4035-a767-826924e2f4e4.jpeg)



This way a wireless system is designed which is autonomous and can monitor as well as control the physical or environmental conditions, such as temperature and humidity and could stream the respective data to the control station. This Wireless Sensor network is bidirectional which enables the control over the sensor activity. This system consists of various units as shown below which are assembled as a whole and works in rhythm for accurate analysis functioning. As this system is equipped with high sensitive sensors, networks with low delay and accuracy governed components. this system is highly reliable for any application.


# Feature
* It uses a capacitive humidity sensor and a thermistor to measure the surrounding air.
* spits out a digital signal on the data pin (no analog input pins needed).
* Good for 20-80% humidity readings with 5% accuracy.
* Good for 0-50 °C temperature readings +-2 °C accuracy.

# Advantages

* Temperature sensors are low-cost, precise, and extremely reliable in repeated experiments.
* They are desirable for both embedded and surface mount applications.
* They have a faster response time because of the lower thermal mass. 
* The vibrating wire type is normally full-interchangeable.
* These devices are used to provide the actual humidity condition within the air at any given point or in any given place.

# Disadvantages

* Non-linear Low voltage Least stable, repeatable Least sensitive

# SWOT Analysis
# STRENGTHS
* Easy to use.
* fast in operation.

# WEAKNESSES
* More sensitive 

# THREATS
* Least stable

# OPPORTUNITIES
* Tracking to determine the pace of  sensor network .

# 4 W's and 1 H

# Who
* sensor should sense the object.
# What
* A  device used to measure temperature. This can be air temperature, liquid temperature or the temperature of solid matter.
# When
* They should be used when you are able to make good thermal contact between the device and what you're measuring.
# Where
* Temperature sensors are used in diverse applications such as food processing, HVAC environmental control, medical devices, chemical handling and automotive under the hood monitoring (e.g., coolant, air intake, cylinder head temperatures, etc.).
# How
* This is situated inside the sensing end of the probe. When heated, the gas expands/liquid heats up which signals the attached rod to move the needle to the temperature being measured.


## High Level Requirements
| ID | Description | Status (Implemented/Future) |
| --- | --- | --- |
| HR01 | System should be able to response in  time | Implemented |
| HR02 | high teamperature range  | Implemented |
| HR03 | System should meet the requrements like accuracy,stability,linearity | Implemented |



## Low Level Requirement
| ID | Description | Status (Implemented/Future) |
| --- | --- | --- |
| LR01 |  System should be able to access data | Implemented |
| LR02 | User should be able to use the device   | Implemented |
| LR03 | System should give the propar data | Implemented |


# Architecture
 In this folder it contain both the process and the product of planning,designing ,flowchart and structures.

## Folder Structure
|Folder             | Description |
|-------------------| -----------------------------------------|
| `1_Behavior Diagrams`   | Block diagram, high level requriment, low level requriment|
| `2_Structure Diagrams`         | high level requriment,low level requriment|



# TestPlane and Output


| Test ID | Description | Input |  output | 
| --- | --- | --- | --- | 
| 01 | Check  status 1 | temperature/humidity | Temp:40.0  humidity:30.0|
| 02 | Check  status 2 | temperature/humidity | Temp:29.0  humidity:36.9 | 
| 03 | Check  status 3 | temperature/humidity | Temp:38.99 humidity:28.76 |







