# 3x3-MacroPad
The MicroPad is a custom 3x3 macro pad that was designed and built from scratch. It uses Seeed XIAO RP2040 microcontroller and runs QMK firmware to allow full customizability keys. This program allows the user to customized the diffrent keys pressed.
This project includes a custom PCB design, CAD case design, and firmware. The case was designed to hold the PCB securely while keeping the design minimal and clean without using a faceplate.
# Why I Made This Project 
I built this project to learn more about hardware design and programming. Specifically, I wanted to practice:

* PCB design using KiCad
* 3D CAD modeling for custom enclosures
* Designing a small keyboard device from scratch

This project helped me understand how hardware, firmware, and mechanical design.
# How to Use the HackPad
+ The macropad will send key presses defined in the QMK firmware keymap.
+ To customize the keys, edit the keymap.c file in the firmware and compile it using QMK.
+ Flash the compiled firmware file (.uf2) to the RP2040 microcontroller.
+ The new keymap will be active after flashing.
# Full CAD Assembly

<img width="666" height="707" alt="Screenshot 2026-03-12 at 10 22 12 PM" src="https://github.com/user-attachments/assets/4ef151a7-32a5-4429-b269-28b95c35784b" />

# PCB Design

<img width="300" height="400" alt="Screenshot 2026-03-12 at 10 25 44 PM" src="https://github.com/user-attachments/assets/5f120504-0d37-4636-86a9-e11a3a4b2bb3" />

<img width="376" height="622" alt="Screenshot 2026-03-12 at 10 26 11 PM" src="https://github.com/user-attachments/assets/46b77a89-c51d-41f1-a737-ed367e2ab41d" />

<img width="374" height="619" alt="Screenshot 2026-03-12 at 10 26 34 PM" src="https://github.com/user-attachments/assets/1afa15e1-5be9-40e8-b141-3ff8f8445f16" />

<img width="738" height="365" alt="Screenshot 2026-03-12 at 10 27 10 PM" src="https://github.com/user-attachments/assets/30cf9970-f5de-410f-bb1a-986f83f6f244" />

# Bill of Materials (BOM)
## Bill of Materials (BOM)

| Component | Quantity | Price (CAD) | Link |
|---|---|---|---|
| XIAO RP2040 | 1 | $14.76 | https://www.seeedstudio.com |
| Switches | 9 | $1.59 | https://www.aliexpress.com/item/1005006814061416.html |
| Keycaps | 9 | $6.67 | https://www.aliexpress.com/item/1005008542056314.html |
| Diodes | 9 | $1.26 | https://www.digikey.ca/en/products/detail/onsemi/1N4148/458603 |
| 0.91" 128x32 OLED Display | 1 | $3.18 | https://www.aliexpress.com/item/1005008640132638.html |
| M3x16mm Screws | 4 | $7.96 | https://www.canadiantire.ca/en/pdp/hillman-philips-pan-head-machine-screw-m3-50-x-16-mm-0612155p.html |
| M3x5x4mm Heatset Inserts | 4 | $5.39 | https://www.aliexpress.com/item/1005008285787978.html |
| PCB (JLCPCB) | 1 | $3.50 | https://cart.jlcpcb.com |
| 3D Printed Case | 1 | $0.00 | Used own 3D Printer |

**Subtotal:** $44.31 CAD  
**Ontario HST (13%):** $5.76 CAD  
**Total Cost:** $50.07 CAD

# Hardware Overview

Microcontroller: Seeed XIAO RP2040

Switches: Cherry MX Switch

Key Layout: 3×3 ortholinear

Firmware: QMK Firmware

Case: Custom designed 3D printed enclosure

# Files Included in This Repository

Firmware - QMK configuration and keymap files

PCB Design - KiCad schematic and PCB layout

CAD Models - 3D enclosure design files and STEP export

BOM - Parts list with purchase links

# Resources
https://blueprint.hackclub.com/hackpad

# License

This project is open-source and available for modification and improvement.
