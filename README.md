# 3D Solar Tracker using Arduino

This project involves the design and implementation of a **3D solar tracking system** using **Arduino**, capable of adjusting a solar panel’s position in both azimuth and elevation directions to **maximize sunlight capture** throughout the day.

## 🔧 Key Features
- **Dual-axis (3D) tracking**: Tracks the sun’s position in both horizontal and vertical directions  
- **Light sensing** using **LDRs (Light Dependent Resistors)**  
- **Servo motors** for real-time panel adjustment  
- **Arduino-based control logic**  
- Increases solar panel efficiency compared to fixed systems

## 🛠️ Components Used
- Arduino UNO  
- 4 x LDR sensors  
- 2 x Servo Motors (SG90 or MG995)  
- Resistors (10kΩ for LDRs)  
- Solar Panel (optional for testing)  
- Breadboard, jumper wires, mounting frame

## ⚙️ Working Principle
- Four LDRs are positioned in a cross formation around a divider to detect sunlight intensity.
- Arduino reads the LDR values and calculates which direction has the most sunlight.
- Based on the difference, servo motors adjust the panel in the X (azimuth) and Y (elevation) directions.
- Continual tracking ensures optimal alignment with the sun.

## 📁 Files Included
- Arduino code (`.ino` file)  
- Circuit diagram (image or schematic)  
- Working video or image (optional)  
- Project documentation (if available)

## 🔋 Applications
- Small-scale solar tracking systems  
- Educational projects in embedded systems and renewable energy  
- Improved efficiency for solar-powered devices

## 📎 Author
Swaroop Shinde  
B.Tech ECE | Embedded Systems & Renewable Tech Enthusiast

---

Let me know if you’d like to add fritzing diagrams, a video demo link, or testing data from different times of the day.
