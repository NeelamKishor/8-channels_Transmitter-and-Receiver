# 📡 8-Channel Transmitter and Receiver with Trims using NRF24L01 and Arduino

This project demonstrates a **wireless 8-channel transmitter and receiver** system using the **NRF24L01** module and **Arduino Nano**. The system is designed for remote control applications such as **robotics, drones, and RC vehicles**, providing **trim functionality** for fine adjustments.

## 🚀 Features
- **8-Channel Wireless Transmission** using **NRF24L01** at **2.4 GHz**.
- **Trim Functionality** for fine control adjustments.
- **EEPROM Storage** to retain trim values after power cycles.
- **Low-Latency Communication** using **SPI protocol**.
- **Customizable and Expandable** for various remote control applications.

## 🛠 Components Used
### **Transmitter (TX)**
- **Arduino Nano** – Main controller.
- **NRF24L01** – Wireless transceiver.
- **Joysticks & Potentiometers** – Control inputs.
- **Trim Buttons** – Adjusts channel sensitivity.
- **EEPROM Storage** – Stores trim values.
- **Power Supply** – 3.3V regulator for NRF24L01.

### **Receiver (RX)**
- **Arduino Nano** – Receives and processes signals.
- **NRF24L01** – Wireless transceiver module.
- **PWM Output Channels** – Control servos, motors, or peripherals.
- **Voltage Regulator (LD1117 3.3V)** – Ensures stable power for NRF24L01.
- **Capacitors & Resistors** – For signal stability and power filtering.

## 🔧 Working Principle
1. **Transmitter Side:**
   - Reads **joystick/potentiometer inputs**.
   - Allows real-time **trim adjustments**.
   - Transmits control signals via **NRF24L01 (2.4 GHz)**.

2. **Receiver Side:**
   - Receives signals from the transmitter.
   - Processes the signals and outputs **PWM** to control servos/motors.
   - Maintains stored **trim settings** using **EEPROM**.

## 📌 Applications
- **Remote-Controlled Vehicles & Drones** 🚁
- **Robotic Arm Control** 🤖
- **Wireless Servo & Motor Control** 🔧
- **Customizable Game Controllers** 🎮

## ⚙️ Installation & Setup
### **1️⃣ Wiring Connections**
- **NRF24L01 (Transmitter & Receiver)**


 
- **Joysticks & Trim Buttons (TX)**

 

- **PWM Output Channels (RX)**

### **2️⃣ Code Upload**
1. **Install required Arduino libraries:**
    ```sh
   Arduino IDE → Library Manager → Install "RF24" & "SPI"

## 🎯 Future Improvements
- 📺 **LCD Display** for real-time feedback.
- 🔋 **Battery Optimization** for longer runtime.
- 📶 **Longer Range Modules** like **NRF24L01+ PA/LNA**.

## 📜 License
This project is **open-source** under the **MIT License**

