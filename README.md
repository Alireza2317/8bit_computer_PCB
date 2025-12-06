# PCB Design of Ben Eater's 8-Bit Computer 🖥️

![KiCad](https://img.shields.io/badge/KiCad-blue?logo=kicad&logoColor=white)
![Hardware](https://img.shields.io/badge/Hardware-PCB_Design-orange)
![License](https://img.shields.io/badge/license-MIT-grey)

A complete **Printed Circuit Board (PCB)** implementation of the famous 8-bit computer architecture (SAP-1) designed by Ben Eater.

Moving from breadboards to a production-ready PCB, this project demonstrates complex signal routing, hierarchical schematic organization, and digital logic design using the **74xx TTL series** chips.

## 📸 3D Render
<p align="center">
  <img src="https://github.com/user-attachments/assets/9e79dd56-1a1e-434d-a4ed-2072bcc259a7" alt="3D Top View" width="800">
</p>

## ⚙️ Technical Specifications
| Feature | Details |
| :--- | :--- |
| **EDA Software** | KiCad |
| **Architecture** | Simple As Possible |
| **Logic Family** | 74LS / 74HC Series (TTL) |
| **PCB Layers** | 2 Layers |
| **Mounting** | Through-Hole Technology (THT) |

## 🧠 Design Challenges & Features
* **Hierarchical Schematics:** The design is broken down into modular logical blocks (Clock, RAM, ALU, Control Logic) using KiCad's hierarchical sheets for maintainability.
* **Complex Routing:** Managing hundreds of data and control lines on a 2-layer board required careful optimization of trace paths to minimize vias and ensure signal integrity.
* **Bus Architecture:** Implements a central 8-bit bus connecting all registers and the Arithmetic Logic Unit.

## 🖼️ Gallery

#### PCB Layout
<p align="center">
  <img src="https://github.com/user-attachments/assets/fcf23314-1296-4016-a03c-5ebc52735a74" alt="PCB Layout" width="700">
</p>

#### 3d View Snapshot
<p align="center">
  <img src="https://github.com/user-attachments/assets/291e1488-833a-4968-a004-251972bc373b" alt="3D Top View" width="800">
</p>


### Schematics (Sneak Peek)

#### Root schematic page
<p align="center">
  <img src="https://github.com/user-attachments/assets/39e5015c-4b0e-4091-8781-f9d2d70c54bb" width="800" alt="root schematics">
</p>

#### RAM Module
<p align="center">
	<img src="https://github.com/user-attachments/assets/1ac22821-a0c0-4070-8ca1-6a5d30e9a24c" width="800" alt="Memory schematics">
</p>


## 🚀 How to Open
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Alireza2317/8bit_computer_PCB
   ```
2. **Open in KiCad:**
   * Launch **KiCad**.
   * Go to `File > Open Project`.
   * Select the `.kicad_pro` file in the root directory.
3. **Explore:**
   * Click the **Schematic Editor** to see the logic.
   * Click the **PCB Editor** to see the physical routing.

## 👏 Acknowledgments
This project is based on the incredible educational series by **Ben Eater**.
* [Ben Eater's Website](https://eater.net/8bit)
* [YouTube Playlist](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU)
