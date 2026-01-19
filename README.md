# Custom Flight Controller
## A completely custom high-efficiency Flight Controller for Drone.
This flight controller is based on STM32F722RET6 MCU and BMI270 Gyro. This is optimized for modern FPV Drones featuring a 4 layer PCB and a dedicated 8-Pin connecter for modern ESC's.

### Hardware Specifications

MCU: STM32F722RET6

Gyro: BMI270 via Serial Peripheral Interface

Storage: W25NO1G

Input Voltage: 3S-6S LiPo (integrated 5V/2A Regulator)

OSD: AT7456E

Features: Buzzer for emergency situation, USB-C Programming, Suitable capacitors, diodes, inductors and resistors

### ESC Connection Guide
Pin 1 : VBAT : Battery Input

Pin 2 : GND : Ground

Pin 3 : Motor 1 : PB4

Pin 4 : Motor 2 : PB5

Pin 5 : Motor 3 : PB0

Pin 6 : Motor 4 : PB1

Pin 7 : Current : PC0

Pin 8 : Telemetry : PC7

### Software Specifications
Compatible with: 
- Betaflight
- Rotorflight
##### Code is given in firmware folder

### PCB:

<img width="718" height="707" alt="Screenshot 2026-01-18 202654" src="https://github.com/user-attachments/assets/c3929aff-342d-4984-a5e8-fce268bee03c" />

### Schematic Diagram:

<img width="1245" height="815" alt="Screenshot 2026-01-19 204419" src="https://github.com/user-attachments/assets/aa7a9e8e-b6c7-4229-a815-c0744976b070" />


### Designed by Safeer Hassan :)
