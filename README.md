# ESP32-S3-DevKitC-1 Hardware Design Project

I’m proud to share my complete **ESP32-S3-DevKitC-1 hardware design project**!  
As a hardware and PCB design engineer, I recently completed a full end-to-end development of a **custom ESP32-based board** — starting entirely from scratch and ending with generating Gerber files.

---

## 🧩 Project Overview

This journey covered every stage of the hardware design process:

- **Library creation** — developed schematic symbols, footprints, and 3D models with proper parameter linking (LCSC, Digi-Key).  
- **Schematic design** — integrated the ESP32, FTDI USB-UART, voltage regulation, USB interface, and all peripheral components.  
- **Stack-up design** — implemented a 4-layer configuration (Signal – Power – GND – Signal) optimized for impedance control and EMI reduction.  
- **High-speed layout** — routed USB 2.0 differential pairs (90 Ω) with controlled impedance, length matching, and via stitching.  
- **Design verification** — performed DRC and high-speed rule checks aligned with JLCPCB manufacturing capabilities.  
- **Fabrication & assembly** — generated Gerber, drill, and pick-and-place files, then fabricated through JLCPCB and successfully assembled.

---

## 🧠 Learning Outcomes

This project was part of an **8-hour practical course by Robert Feranec**, through which I learned advanced:

- **Altium Designer workflows** — rules setup, polygon management, via stitching, and pullback distance.  
- **Signal integrity and high-speed routing** techniques for real-world applications.  
- **Professional documentation** and fabrication preparation practices.

---

## 💡 Highlights

- Complete ESP32-S3 hardware design from scratch  
- Fully verified for manufacturing at JLCPCB  
- Includes USB, UART, and power management sections  
- Proper 4-layer stack-up and impedance control  
- Tested and validated assembled prototype

---

## 📸 Gallery

| Schematic Overview | PCB Layout | Assembled Board |
|--------------------|-------------|------------------|
| !1.jpg | ![Layout](images/layout.png) | ![Assembled Board](images/assembled.png) |

> 📝 *Replace the image paths above with your actual uploaded image filenames.*

---

## 🏭 Fabrication

- **Manufacturer:** JLCPCB  
- **Layers:** 4  
- **Material:** FR-4  
- **Finish:** ENIG  
- **Board Size:** Custom ESP32 DevKitC-compatible  
- **Via Type:** Through-hole + stitched vias  

---

## 🙏 Acknowledgment

Huge thanks to **Robert Feranec** for the detailed, hands-on guidance that made this project a reality.  
Watching a design come to life from schematic to a functional PCB is an amazing feeling for any engineer.

---

## 🧾 License

This project is shared for **educational and portfolio purposes**.  
Please give proper credit if referencing or reusing parts of the design.

---

### 📬 Contact

For collaboration or inquiries, feel free to reach out via [LinkedIn](https://linkedin.com) or email.

---

