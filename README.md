# 📡 MC1496 Balanced Demodulator – PCB Design (Altium Designer)

This repository contains the complete design of a **Balanced Demodulator using the MC1496 IC**, fully implemented in **Altium Designer**.  
The project includes schematic design, PCB layout (2D & 3D), simulation-ready files, and a custom parts library.

---

## 📌 Features

- ✔️ Complete implementation based on the MC1496 balanced modulator/demodulator topology  
- ✔️ Fully designed schematic (Altium .SchDoc)  
- ✔️ PCB Layout in both **2D and 3D**  
- ✔️ A custom **Integrated Library (.IntLib)** containing all footprints used  
- ✔️ Manual routing with clean component placement  
- ✔️ Feedthrough capacitors, resistor networks, trimmer potentiometer (null adjust)  
- ✔️ Input/Output headers for easy testing  
- ✔️ Professional project structure for documentation & portfolio use  

---

## 🧩 Hardware Overview

### 🔹 **Main IC**
- **MC1496** — Balanced Modulator/Demodulator  
- Used for AM, DSB-SC demodulation & modulation applications

### 🔹 **Power Rails**
- **+12V**
- **–8V**
- **GND (0V)**

### 🔹 **Inputs**
- Carrier Input (**VC**)
- Signal Input (**VS**)

### 🔹 **Outputs**
- Differential Output:
  - **+Vout**
  - **–Vout**

### 🔹 **Key Components**
- Resistors: _1kΩ, 3.9kΩ, 51Ω, 10kΩ, 50kΩ (trimmer)_  
- Capacitors: _100nF decoupling_  
- MC1496 DIP package footprint  
- Custom pin headers for external interfacing  

---

## 📐 Schematic Overview

The schematic follows the standard MC1496 demodulator design including:

- Biasing resistors  
- Null adjustment potentiometer  
- Input coupling capacitors  
- Balanced modulator input/output configuration  
- Proper grounding and reference routing  

📁 File: `Sheet1.SchDoc`  
(Located in `/schematic/` folder)

---

## 🛠️ PCB Layout

The PCB was fully designed in Altium Designer with:

- 2-layer FR4 board  
- Clean routing & trace length management  
- Proper decoupling close to MC1496  
- Silkscreen labeling for all components  
- 3D visualization to verify mechanical placement  

### 📸 Included Images (located in `/images/`):
- **Top 2D layout**
- **3D Model**
- **Component placement**
- **Routing plan**

---

## ▶️ How to Open the Project

### **In Altium Designer:**
1. Open:  
   `PCB_Project.PrjPcb`
2. Load schematic:  
   `Sheet1.SchDoc`
3. Load PCB layout:  
   `*.PcbDoc`
4. Load custom library if needed:  
   `Integrated_Library1.IntLib`
5. View PCB in 3D:  
   **View → 3D Layout Mode (Shortcut: 3)**

---

## 🎯 Notes

- This project is suitable for RF, Modulation, and Communication Systems courses  
- The design is **entirely done manually**—no auto-router  
- All footprints were verified before placement  
- The repository is structured for easy review by instructors and recruiters  

---

## 👤 Author
**Mohammad Hossein Ahmadi**

