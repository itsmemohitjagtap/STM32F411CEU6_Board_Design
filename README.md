
# STM32F411CEU6 Board Design

A custom **STM32F411CEU6 development board** designed in **Altium Designer Professional 25.2.1**.  
This hardware design focuses on compactness, reliability, and ease of firmware development for embedded systems.

---

## 🧠 Overview

This repository contains the complete schematic, PCB layout, and documentation for a custom **STM32F411CEU6 (ARM Cortex-M4)** based board.  
The design includes USB connectivity, SWD programming support, and essential GPIO headers for prototyping and experimentation.

---

## ⚙️ Key Features

- **Microcontroller:** STM32F411CEU6 (ARM Cortex-M4, 100 MHz)
- **Programming Interface:** SWD (Serial Wire Debug)
- **Power Input:** 5V via USB
- **Peripherals:**
  - USB data protection and filtering circuit
  - 12 MHz crystal oscillator with capacitors
  - Voltage regulator circuit
  - Power and status LEDs
  - GPIO expansion header
- **Design Checks:** ERC passed successfully ✅  
- **EDA Tool:** Altium Designer Professional 25.2.1

---

## 📑 Bill of Materials (BOM)

See BOM file for the complete component list, which includes:
- STM32F411CEU6 microcontroller  
- 12 MHz crystal oscillator and load capacitors  
- USB Type-A connector and ESD protection  
- LDO voltage regulator (5V → 3.3V)  
- SWD header and GPIO expansion pins  
- LEDs, resistors, and bypass capacitors

---

## 🧮 Schematic Overview

The schematic covers:
- Power regulation and filtering  
- USB data interface with ESD protection  
- Clock generation circuit  
- MCU core with SWD, BOOT0, and NRST  
- GPIO expansion headers  

---

## 🪛 PCB Layout Preview

**Highlights:**
- Differential pair routing for USB lines  
- Compact 4-layer layout  
- Short trace design for crystal stability  
- Star-grounding and power filtering for noise reduction  

---

## ✅ Design Verification

- **ERC (Electrical Rule Check):** Passed successfully  
- **DRC (Design Rule Check):** No violations  
- **3D Model:** Fully supported in Altium Designer  

---

## 🧰 Software Used

- **Altium Designer Professional 25.2.1**
- **Library:** Custom component footprints and 3D models
- **Output Files:** Gerbers, NC drill, assembly drawings

---

## 👨‍💻 Designer

**Designed by:** Mohit Jagtap  
Electronics & Telecommunication Engineering  
Dr. D. Y. Patil Institute of Engineering Management and Research, Akurdi, Pune 
**Tool:** Altium Designer Professional 25.2.1

---

## 🌟 Contribution

Feel free to submit issues, suggest improvements, or contribute additional board features.  
Let’s grow open-source embedded hardware together.

---

## 🧩 Tags
`STM32` • `Altium` • `Embedded Hardware` • `PCB Design` • `ARM Cortex-M4` • `Electronics`

---

