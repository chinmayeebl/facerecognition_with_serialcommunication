# facerecognition_with_serialcommunication
<img src="robo.png" alt="Image" width="300"/>
https://github.com/chinmayeebl/facerecognition_with_serialcommunication/assets/143340347/22fd133f-b766-4992-876d-9a389b952f66 

## Project Description

This project combines three key components: 
1. *Facial Recognition Model Implementation*: We have developed a facial recognition model to identify individuals.
2. *Python-Arduino Integration via Serial Communication*: Python scripts are interfaced with Arduino microcontrollers using serial communication, enabling seamless interaction between the two platforms.
3. *Peripheral Integration with Arduino*: Various peripherals such as LCD displays and servo motors are interfaced with Arduino, enhancing the functionality and capabilities of the system.


# Facerecognise.py

This Python script (facerecognise.py) provides functionality for face recognition utilizing OpenCV's face detection algorithms. It communicates with an Arduino board via serial communication to actuate peripherals based on the recognized faces.


## Requirements:
- Python 3 and above
- OpenCV
- pySerial
- Arduino board

---

# Arduino Serial Communication (arduinoserial)

This Arduino sketch (arduinoserial) is designed to receive commands from a Python script via serial communication and actuate peripherals connected to an Arduino Mega board accordingly.


## Requirements:
- Arduino IDE  version 2.0 and above
- Arduino Mega 2560 or other Arduino boards.


