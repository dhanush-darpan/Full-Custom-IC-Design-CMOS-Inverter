# Full-Custom-IC-Design-CMOS-Inverter 
### CMOS Inverter – Schematic, Layout, and Verification

---

## Overview

This repository contains a **full-custom analog VLSI design project** implemented using **Cadence Virtuoso** design tools.  
The project focuses on the **design, layout, and physical verification of a CMOS inverter**, following standard **custom IC design flow** practices.

The work includes:
- Transistor-level schematic design  
- Full-custom layout creation  
- Design Rule Check (DRC)  
- Layout Versus Schematic (LVS) verification  
- Simulation and waveform analysis  
- Design snapshots for documentation and review  

This repository is intended for **academic learning, portfolio demonstration, and reference** in full-custom analog and VLSI design workflows.

---

## Design Objectives

- To understand and implement **full-custom CMOS design methodology**
- To design a **CMOS inverter** at transistor level
- To create a **layout compliant with foundry design rules**
- To perform **DRC and LVS verification**
- To validate functionality using **analog simulation**
- To document the design flow and results in a structured manner

---

## Tools & Technology

- **EDA Tool**: Cadence Virtuoso (Analog Design Environment)
- **Verification**: Cadence Assura (DRC & LVS)
- **Simulation**: Cadence ADE
- **Design Style**: Full-custom (transistor-level)
- **Technology Node**: Foundry-specific PDK (configured locally)

> **Note:** The Process Design Kit (PDK) is not included in this repository due to licensing restrictions.

---

## Repository Structure

Analog - full custom design/
├─ Inverter/
├─.cadence/ # Cadence user/session data (auto-generated)
├─ .assura* # Assura DRC/LVS run data
├─ layout/ # Full-custom inverter layout
├─ schematic/ # Transistor-level schematic
├─ symbol/ # Symbol view
├─ extracted/ # Extracted view (post-layout)
├─ simulation/ # ADE simulation states and results
├─ xStrmOut_cellMap.txt # Stream-out mapping file



---

## Design Flow Followed

1. **Schematic Design**  
   CMOS inverter designed using PMOS and NMOS transistors with appropriate sizing.

2. **Symbol Creation**  
   Symbol view generated for hierarchical and reusable design.

3. **Layout Design**  
   Full-custom layout implemented using poly, diffusion, and metal layers, ensuring symmetry and matching.

4. **Physical Verification**  
   - **DRC**: Layout verified against foundry design rules  
   - **LVS**: Layout netlist matched with schematic netlist

5. **Post-Layout Validation**  
   Extraction and functional verification through simulation and waveform analysis.

---

## Verification Status

| Verification Step | Status |
|------------------|--------|
| Schematic Design | Completed |
| Layout Design | Completed |
| DRC | Clean |
| LVS | Matched |
| Simulation | Verified |

---

## Documentation

The `Snaps/` directory includes:
- Schematic screenshots  
- Layout views  
- DRC and LVS reports  
- Simulation waveforms  

These artifacts support **design validation, review, and academic evaluation**.

---

## Version Control Notes

This repository includes **only design-relevant artifacts**.  
Generated tool caches, temporary files, and PDK data must be excluded using `.gitignore`.

Recommended exclusions:
- `.cadence/`
- `.assura*`
- Temporary simulation files
- PDK and technology libraries

---

## Intended Use

- Academic coursework and laboratory submissions  
- Full-custom analog VLSI learning reference  
- Interview and professional portfolio demonstration  
- Foundation for advanced analog and mixed-signal block design

---

## License

This project is intended for **educational and academic use only**.  
Fabrication or redistribution using proprietary PDKs must comply with foundry and Cadence licensing agreements.

---

## Author

**Dhanush Darpan Y**

---

## Conclusion

This project demonstrates a complete **full-custom CMOS inverter design cycle**, from schematic creation to physical verification using industry-standard EDA tools. It reflects a structured and disciplined approach to analog VLSI design, aligned with best practices followed in academic and professional semiconductor environments. The repository serves as a strong foundation for extending into more complex full-custom analog and mixed-signal designs.

---
