# LED Simulation using Arduino  

## 🛠 Project Description  
This project demonstrates how to control multiple LEDs using an Arduino Uno and a breadboard. The LEDs are connected to the Arduino's digital pins and can be programmed to blink in different patterns.  

## 📸 Circuit Diagram  
![LED Simulation](Led%20simulation%20using%20ARDUINO.png)  

## 🔧 Components Required  
- Arduino Uno  
- Breadboard  
- 5 LEDs (Red & Green)  
- 5 Resistors (220Ω each)  
- Jumper wires  

## 🔌 Circuit Connections  
| **Arduino Pin** | **LED Number** | **Connection** |
|---------------|--------------|-------------|
| 2            | LED 1        | Anode (+) |
| 3            | LED 2        | Anode (+) |
| 4            | LED 3        | Anode (+) |
| 5            | LED 4        | Anode (+) |
| 6            | LED 5        | Anode (+) |
| GND          | All LEDs     | Cathode (-) |

Each LED is connected in series with a **220Ω resistor** to limit the current.

**🚀 How to Run**
Connect the circuit as per the wiring diagram.
Open Arduino IDE.
Copy and paste the code from the code file into the IDE.
Select the correct board (Arduino Uno) and port.
Click Upload to flash the code onto the board.
Observe the LEDs blinking in sequence!

**🎯 Features**
✅ Blinking LEDs in a sequential pattern.
✅ Easily expandable for more LEDs.
✅ Demonstrates the use of digital pins.
