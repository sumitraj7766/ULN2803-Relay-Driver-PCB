# 8-Channel Relay Driver PCB using ULN2803A

A professional 8-channel relay driver PCB designed using KiCad and ULN2803A Darlington transistor array IC for embedded systems and industrial automation applications.

---

# Project Overview

This project is an 8-channel relay control board capable of driving multiple relays using a ULN2803A driver IC.

The PCB was fully designed in KiCad including:

- Schematic Design
- PCB Layout
- Routing
- Component Placement
- 3D PCB Visualization
- Hardware Documentation

---

# Features

- 8 Relay Outputs
- ULN2803A Relay Driver
- LED Status Indicators
- Compact PCB Design
- Mounting Holes
- Through-Hole + SMD Components
- Industrial Style Layout
- 3D PCB Visualization

---

# Tools Used

| Tool | Purpose |
|---|---|
| KiCad | PCB & Schematic Design |
| PCB Editor | Routing & Layout |
| 3D Viewer | PCB Visualization |

---

# Hardware Specifications

| Parameter | Value |
|---|---|
| PCB Layers | 2 |
| Relay Channels | 8 |
| Driver IC | ULN2803A |
| Relay Type | Omron G5LE-1 |
| PCB Software | KiCad |
| Mounting Support | Yes |

---

# Schematic Design

<img width="1370" height="735" alt="Screenshot 2026-05-25 135750" src="https://github.com/user-attachments/assets/dc88f5a2-296f-4119-a364-7c133ef12ebf" />


The schematic includes:

- ULN2803A driver IC
- 8 relay channels
- LED indicators
- Input connector headers
- Power filtering capacitor
- Current limiting resistors

---

# PCB Layout
<img width="1343" height="723" alt="Screenshot 2026-05-25 135654" src="https://github.com/user-attachments/assets/4a0f3e05-bf15-47e3-a6fa-359de99843af" />



PCB design includes:

- Clean routing
- Proper relay placement
- Compact component arrangement
- Mounting holes
- Input and output connectors

---

# 3D PCB View

## Front View

<img width="361" height="409" alt="Screenshot 2026-05-25 135628" src="https://github.com/user-attachments/assets/89362cc6-a90f-4d1d-9045-e8775c626288" />


---

## Angled View

![3D Angle](Images/pcb_3d_angle.png)

---

# Bill of Materials (BOM)

| Component | Quantity |
|---|---|
| ULN2803A IC | 1 |
| Omron G5LE-1 Relays | 8 |
| LEDs | Multiple |
| Resistors | Multiple |
| Capacitors | 2 |
| Connectors | Multiple |
| Mounting Holes | 4 |

---

# Folder Structure

```text
ULN2803_RELAY_CARD/
│
├── README.md
├── LICENSE
│
├── Images/
│   ├── schematic.png
│   ├── pcb_layout.png
│   ├── pcb_3d_front.png
│   └── pcb_3d_angle.png
│
├── Hardware/
│   ├── ULN2803_RELAY_CARD.kicad_sch
│   ├── ULN2803_RELAY_CARD.kicad_pcb
│   ├── *.kicad_pro
│   └── Gerber/
│
└── BOM/
    └── bom.csv
