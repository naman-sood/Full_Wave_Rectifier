# AC to DC Bridge Rectifier – PSpice Simulation  

## 📌 Project Overview  
This project demonstrates a **full-wave bridge rectifier** using **PSpice**. The circuit converts an **AC signal** into **DC output** using a diode bridge configuration. The simulation analyzes the rectified waveform and ripple voltage with and without a capacitor filter.  

## 🔧 Circuit Components  
- **AC Voltage Source**: 5V amplitude, 1kHz frequency  
- **Diodes (1N4002 x 4)**: Forms the bridge rectifier  
- **Load Resistor (1kΩ)**: Converts rectified current into voltage  
- **Capacitor (Optional, 1000µF)**: Smooths the DC output  

## ⚡ Simulation & Results  
- **Without Filter**: Pulsating DC output  
- **With Filter**: Smooth DC with reduced ripple  
- **Measured Parameters**: Output voltage, ripple, transient response  

## 🖥️ How to Run the Simulation  
1. Open **PSpice** and load the schematic file (`.dsn`).  
2. Set up **Transient Analysis** (0–10ms) to observe waveforms.  
3. Run the simulation and compare output voltages.  

## 📸 Screenshots  
![Screenshot 2025-02-21 152109](https://github.com/user-attachments/assets/33aed0cd-9917-4489-8bfd-4f36a2a97cd7)
![image](https://github.com/user-attachments/assets/1717f559-ef1d-4f90-b2c3-b721c330f9b6)



## 🔗 GitHub Repository  
[Click here to access the project](https://github.com/yourusername/AC-DC-Rectifier-PSpice)  

---
✍️ Created by **Naman Sood**
