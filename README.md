# 🚗 Smart Parking System using Arduino (IoT Project)

## 📌 Project Overview
This project is a **Smart Parking System** built using Arduino UNO, IR sensors, Servo motor, and an LCD display.  
It automatically detects available parking slots, opens/closes the barrier gate, and displays the number of slots left on the LCD screen.  

## 🛠 Components Used
- Arduino UNO
- IR Sensors (2x)
- Servo Motor
- LCD Display (16x2) with I2C module
- Breadboard & Jumper Wires
- Power Supply

## ⚡ Circuit Diagram
<img width="644" height="408" alt="circuit" src="https://github.com/user-attachments/assets/14f30892-617a-4b06-a262-cb3584301667" />
<img width="3784" height="3000" alt="circuit_image" src="https://github.com/user-attachments/assets/df3513be-6b40-468c-b555-ab51d49b831c" />



## 📷 Project Images
### Prototype
![iot1](https://github.com/user-attachments/assets/93ba2d58-f869-4215-b67d-dfa6816e4bd6)


### Working Model
![iot2](https://github.com/user-attachments/assets/33085451-e31a-40dc-8fb2-96b904613969)

## 🔌 Working Principle
1. **IR Sensor 1** detects when a vehicle arrives at the entrance.  
2. If slots are available:
   - Servo motor lifts the gate.  
   - Slot count decreases by 1.  
3. **IR Sensor 2** detects when a vehicle exits.  
   - Servo motor lifts the gate.  
   - Slot count increases by 1.  
4. If slots are full, the LCD displays `"SORRY :( Parking Full"`.  

## 📟 LCD Output
- When parking is empty: `SLOT EMPTY`
- When parking is available: `WELCOME - Slots Left: n`

## 👨‍💻 Developed By: Varun M C
📅 Year: 2025
