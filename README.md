**🔌 Network Lead Tester PCB Design**

**📖 Overview**

This project presents the PCB layout design of a Network Lead Tester using the NE555 Timer and CD4017 Decade Counter. The circuit is designed to verify the continuity and correct wiring sequence of RJ45 Ethernet cables through sequential LED indication.

The PCB layout was designed using Autodesk EAGLE, including component placement, manual trace routing, and board organization based on the provided schematic.

**✨ Features**

- Single-layer PCB layout
- RJ45 Ethernet cable testing
- Sequential LED indication
- Manual component placement
- Manual bottom-layer routing
- Through-hole PCB design

**⚙️ Working Principle**

- The **NE555 Timer** operates in astable mode to generate clock pulses.
- The **CD4017 Decade Counter** receives these pulses and activates one output at a time.
- Both ends of an **RJ45 Ethernet cable** are connected to the tester.
- If the cable is wired correctly, the LEDs illuminate sequentially from **1 → 8**.
- Any open circuit, crossed pair, or incorrect wiring changes the LED sequence, allowing faults to be identified quickly.

**🛠️ Components Used**

- NE555 Timer IC
- CD4017 Decade Counter IC
- RJ45 Connectors
- LEDs
- Resistors
- Capacitors
- 9V Battery Connector

**💻 Software Used**

- Autodesk EAGLE

**🎯 Skills Demonstrated**

- PCB Layout Design
- Schematic Interpretation
- Component Placement
- Manual PCB Routing
- Through-Hole PCB Design
- PCB Documentation

**🎯 Applications**

- Ethernet (LAN) cable testing
- RJ45 wiring verification
- Network cable continuity testing
- Educational electronics and networking projects

**📌 Note**

The circuit schematic was provided as part of a PCB design exercise. This project demonstrates the PCB layout development process, including component placement and manual routing using Autodesk EAGLE.
