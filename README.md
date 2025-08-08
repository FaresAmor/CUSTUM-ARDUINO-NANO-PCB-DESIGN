# Custom Arduino Nano PCB Design (Altium Designer)

## Overview  
This project features a **custom PCB design** inspired by the classic **Arduino Nano**.  
It integrates the **ATmega328P-AU** microcontroller, a **16 MHz crystal oscillator (CSTCE16M0V53-R0)**, and the **FT232RL USB-to-UART bridge** for USB programming and communication.

The board uses a **Mini USB Type-B port** for power and data, regulated by a **UA78M05IDCYR 5V linear regulator**, ensuring stable power delivery.

Designed with **Altium Designer**, this board targets embedded applications needing a compact and reliable Arduino Nano compatible platform.

## Components Used  
- **Microcontroller:** ATmega328P-AU  
- **Crystal Oscillator:** CSTCE16M0V53-R0 (16 MHz)  
- **USB-to-UART Bridge:** FT232RL  
- **Voltage Regulator:** UA78M05IDCYR (5V)  
- **USB Connector:** Mini USB Type-B  
- **Programming Interface:** ICSP header  
- **Reset Button:** Manual reset switch  
- **Passive Components:** Resistors, capacitors including decoupling capacitors  

## Features  
- Arduino Nano compatible form factor and pinout  
- Precise 16 MHz clock source  
- FT232RL USB to UART bridge for programming and serial communication  
- Stable 5V power supply with UA78M05IDCYR regulator  
- Mini USB Type-B port for power and communication  
- ICSP header for bootloader programming and debugging  
- Compact and manufacturable PCB layout  
- Complete design using Altium Designer  

## Files Included  
- Altium Designer project files (`.SchDoc`, `.PcbDoc`)  
- Gerber files for PCB fabrication  
- Bill of Materials (BOM)  
- PDF schematics and assembly drawings  

## How to Use  
1. Open the project in **Altium Designer**.  
2. Review schematic and PCB layout files.  
3. Check design rules, board outline, and component placement.  
4. Generate Gerber and NC drill files for manufacturing.  
5. Assemble the PCB.  
6. Program the ATmega328P using:  
   - The **FT232RL USB interface** via mini USB port, or  
   - The **ICSP header** with an external programmer.  

## Preview

### Top Layer  
![Top View](https://github.com/FaresAmor/Custom_Arduino_Nano_PCB/blob/main/top.png)

### Bottom Layer  
![Bottom View](https://github.com/FaresAmor/Custom_Arduino_Nano_PCB/blob/main/bottom.png)

## Contribution  
Feel free to fork, modify, and contribute improvements!  
If you find any bugs or have suggestions, please open an issue or submit a pull request.

---

> 💡 **Tip:** This custom Arduino Nano design is perfect for compact embedded projects requiring USB connectivity and stable 5V power supply.

