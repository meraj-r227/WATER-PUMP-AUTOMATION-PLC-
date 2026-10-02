# WATER-PUMP-AUTOMATION-PLC-
A PLC-based automation project for smart water supply management. This system intelligently switches between a rainwater harvesting tank and the municipal water network based on tank levels using sensors (S1, S2) and a pump, ensuring a continuous water supply for a building.


## System Diagram

![PLC Water Tank Control System](https://github.com/meraj-r227/WATER-PUMP-AUTOMATION-PLC-/blob/main/images/ChatGPT%20Image%20%DB%B1%DB%B0%20%D9%85%D9%87%D8%B1%20%DB%B1%DB%B4%DB%B0%DB%B5%D8%8C%20%DB%B1%DB%B0_%DB%B3%DB%B1_%DB%B1%DB%B0.png)


# Smart Water Supply Management System (PLC)

**Logic:**
This project presents a PLC-based automation system designed to manage the water supply for a building using two sources: the municipal water network and a rainwater harvesting tank. 

**System Logic:**
- The system monitors the water level in the main tank using two sensors (S1 for High Level, S2 for Low Level).
- **Rainwater Mode:** If there is sufficient rainwater in the tank (above S1), pressing the START button activates the pump to supply the building. The municipal water valve remains closed.
- **Municipal Water Mode:** If the rainwater tank is empty (below S2) or insufficient, the pump is automatically turned off, and the municipal water valve opens to ensure an uninterrupted water supply to the building.

**Hardware & Components:**
- PLC Controller
- Pump
- Solenoid Valve (for Municipal Water)
- Pressure Tank
- Float/Limit Switches (S1, S2)
- START Push Button

