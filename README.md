# TP5100 1S Li-Ion Battery Charger (TP5100-1S-Charger)

A dedicated, compact switch-mode lithium-ion battery charging board based on the **TP5100** synchronous step-down charging management IC, designed in KiCad with full production Gerbers and documentation.

---

## Features

- **High-Efficiency Switch-Mode Charging**:
  - Utilizes the TP5100 buck switching management IC operating at high switching frequency (up to 2A charge current).
  - Superior thermal performance and energy efficiency compared to linear chargers (such as the TP4056).
- **1S Lithium-Ion Cell Profile**:
  - Configured for single-cell 4.2V float voltage charging.
  - Constant Current (CC) / Constant Voltage (CV) multi-stage charging profile with pre-conditioning trickle charge for over-discharged cells.
- **Protection & Monitoring**:
  - Dual LED charging status indicators (Charging / Standby & Complete).
  - Input over-voltage and thermal shutdown protection.
- **Manufacturing-Ready Production Files**:
  - Pre-generated RS-274X Gerber layers and Excellon NC drill files ready for standard PCB fabrication.

---

## Hardware Specification

| Parameter | Value | Unit |
| :--- | :--- | :--- |
| **Charger Controller** | TP5100 | — |
| **Input Voltage Range** | 5.0 – 18.0 | V DC |
| **Battery Configuration** | 1S (1 Cell) | — |
| **Float Voltage** | 4.2 | V |
| **Charge Current** | Configurable up to 2.0 | A |
| **Architecture** | Synchronous Buck Switching | — |
| **PCB Form Factor** | 2-Layer FR4 (1.6 mm thickness, 1 oz copper) | — |

---

## Project Structure

```text
TP5100-1S-Charger/
├── Schematic.pdf                     # Complete electrical schematic
├── front.png                         # 3D PCB front render
├── back.png                          # 3D PCB back render
├── why.txt                           # Project inception note
├── TP5100_1S_Charger.kicad_sch       # KiCad schematic design
├── TP5100_1S_Charger.kicad_pcb       # KiCad PCB board layout
├── TP5100_1S_Charger.kicad_pro       # KiCad project file
├── TP5100_1S_Charger-F_Cu.gbr        # Top copper layer
├── TP5100_1S_Charger-B_Cu.gbr        # Bottom copper layer
├── TP5100_1S_Charger-F_Mask.gbr      # Top solder mask
├── TP5100_1S_Charger-B_Mask.gbr      # Bottom solder mask
├── TP5100_1S_Charger-F_Silkscreen.gbr# Top silkscreen
├── TP5100_1S_Charger-B_Silkscreen.gbr# Bottom silkscreen
├── TP5100_1S_Charger-Edge_Cuts.gbr   # Board contour outline
├── TP5100_1S_Charger-PTH.drl         # Plated through-hole drill file
├── TP5100_1S_Charger-NPTH.drl        # Non-plated through-hole drill file
├── .gitignore                        # Git ignore rules
└── README.md                         # Project documentation
```

---

## License

Open hardware design. All rights reserved by the author.
