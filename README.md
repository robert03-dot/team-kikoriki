# Proiect: Asamblarea robotului 4WD Omni-Directional Mobile Robot Kit

## Echipa
- Nume echipă: kikoriki
- Moto Echipa: Puterea se mișcă în toate direcțiile.
## Descriere generală
Scopul proiectului este asamblarea și testarea robotului 4WD Omni-Directional Mobile Robot Kit, în cadrul laboratorului APD.  
Documentația include pașii de montaj, configurare, testare și eventuale îmbunătățiri aduse.

---

## Checklist componente


Exemplu:
| Nr. | Componentă | Cod / Denumire | Cantitate | Accesorii |
|-----|-------------|----------------|------------|-------------|
| 1 | 100mm Plastic Omni Wheel | 14041 | 4 |  |
| 2 | Screws Accesories for 10mm Omni Wheels | 80020 | 1 |  |
| 3 | Plug Converter | 76008 | 1 | (EU, US, AU, UK Standard) |
| 4 | Hex Screwdrivers | 95002 | 1 | 2mm, 3mm, 4mm, 5mm |
| 5 | Spanner | 95003 | 1 | 8-10mm |
| 6 | NI-MH Battery Charger, 1000mA | 76007 | 1 |  |
| 7 | Arduino USB Cable | 71005 | 1 |  |

---
<img width="844" height="356" alt="image" src="https://github.com/user-attachments/assets/18c5052c-df50-4a60-8f32-ff9a4dc5a259" />
<img width="872" height="715" alt="image" src="https://github.com/user-attachments/assets/e7ecf5ca-f6bd-469b-9433-786e283ce7b0" />


The picture above shows all of the I/O lines and Connectors on the controller, which includes:

􀂃 One Regulated Motor Power Input Terminal (6v to12v)

􀂃 One Unregulated Servo Power Input Terminal (you supply regulated 4v to 7.2v)

􀂃 One Servo input power selection jumper

􀂃 One Serial Interface Module Header for APC220 Module

􀂃 Two DC Motor Terminals – Handles motor current draw up to 2A, each terminal

􀂃 One IIC/TWI Port – SDA, SCL, 5V, GND

􀂃 One Analog Port with 8 analog inputs – one input is tied internally to the supply voltage

􀂃 One General Purpose I/O Port with 13 I/O lines – 4,5,6,7 can be used to control motors

􀂃 One Reset Button

􀂃 Jumper bank to Enable/Disable Motor Control

![WhatsApp Image 2025-12-03 at 16 35 29](https://github.com/user-attachments/assets/0bd6d82f-5a5e-40de-8dfd-6c24e73073b5)

<img width="572" height="324" alt="image" src="https://github.com/user-attachments/assets/0c23f254-94fe-4848-a16e-01ffc970c1bf" />

Descriptions

The 4WD Omni-Directional Arduino Compatible Mobile Robot Kit includes the Arduino IO Expansion
V1.2 and gives you extra ease to connect device such as sensors, servo and RS485 device.
This sensor expansion board is able to easily connect a number of commonly used sensors.
Features
 14 steering gear interface

 8 analog IO port and power

 6 PWM interface

 1 servo external power supply terminal

 5 External power supply input pin

 RS485 interface

 Reset button

 Wireless data-transmission interface

Specifications
 Microcontroller: Arduino IO Expansion V1.2

 Module power supply: +5 V

 Servo power supply: +5 V

 Module size: 53 x 70mm

 Weight: 33.5g

Compatibility
 Arduino Mega

 Arduino Duemilanove (168 and 328)

 Arduino Diecimila

 Arduino I/O

 Arduino LCD

 Arduino Motor

 Arduino Ethernet

Brief introduction of Omni-wheel
Omni-directional wheels are unique as they are able to roll freely in two directions .It can ether
roll like a normal wheel or roll laterally using the wheels along its circumference.Omni-direction
wheels allow a robot to convert from a non-holonomic to a holonomic robot.A non-holonomic
robot that uses normal wheels has only 2 out of 3 controllable degrees-of-freedom which
are,moving forward/backwards and rotation.Not being able to move side ways makes a robot
slower and less efficient in reaching its given goal. The holonomic omni-directional wheels are
able to overcome this problem,as it it a highly maneuverable.Unlike normal non-holonomic
robot,the holonomic omni-directional robot can move in an arbitrary direction continuously
without changing the direction of the wheels.It can move back and forth,slidewaysmand rotates
at the same position. 

<img width="542" height="429" alt="image" src="https://github.com/user-attachments/assets/45645a21-ad70-4de7-ba52-6149948a1e71" />

## Asamblare pas cu pas
Video Tutoriale si imagini poate chiar de la voi 

---

## Configurare software
- Platformă: Arduino IDE / Python / altă platformă
- Librării folosite:
- Servo.h
- LSS-Config
- Adafruit_MotorShield
- Exemple de rulare:

# Compilare și upload
TODO

# ETC



## Progres 
## Progres echipă

| Nr. | Etapă                         | Descriere scurtă                                  | Status | Data finalizării |
|-----|-------------------------------|--------------------------------------------------|---------|------------------|
| 1 | Verificare componente          | Inventarierea pieselor și verificarea integrității | ✅ |  |
| 2 | Montaj mecanic                 | Asamblarea bazei, fixarea motoarelor, șuruburi etc. |  ❌ |  |
| 3 | Conectare electronică          | Conectarea controlerului, cabluri, alimentare     |  ❌ |  |
| 4 | Test inițial mișcare           | Verificarea mișcărilor de bază / cod test         | ❌ |  |
| 5 | Configurare software           | Instalare librării, upload cod, calibrare         | ❌ |  |
| 6 | Test final                     | Verificare completă a funcționării robotului      | ❌ |  |
| 7 | Documentare și imagini         | Scriere README, poze, diagrame, linkuri utile     | ❌ |  |
| 8 | Prezentare finală              | Demonstrație funcțională în laborator             | ❌ |  |

Legenda status:  
✅ = Finalizat  ⏳ = În desfășurare  ❌ = Neînceput
