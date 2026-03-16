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
<img width="375" height="622" alt="Screenshot 2026-03-16 at 6 08 25 PM" src="https://github.com/user-attachments/assets/90fbf990-5229-43e9-b7fe-01ea40425d56" />

<img width="378" height="615" alt="Screenshot 2026-03-16 at 6 07 51 PM" src="https://github.com/user-attachments/assets/98b46507-b562-420a-a5a6-fff200dd19a5" />

<img width="461" height="764" alt="Screenshot 2026-03-16 at 6 07 35 PM" src="https://github.com/user-attachments/assets/1f5b73fa-a9ef-4682-9a9c-2cb75b3554fc" />

<img width="738" height="365" alt="Screenshot 2026-03-12 at 10 27 10 PM" src="https://github.com/user-attachments/assets/30cf9970-f5de-410f-bb1a-986f83f6f244" />

# Bill of Materials (BOM)

| Component | Quantity |
|-----------|----------|
| XIAO RP2040 | 1 |
| Switches | 9 |
| Keycaps | 9 |
| Diodes | 9 |
| 0.91" 128x32 OLED Display | 1 |
| M3x16mm Screws | 4 |
| M3x5x4mm Heatset Inserts | 4 |
| PCB (JLCPCB) | 1 |
| 3D Printed Case | 1 |


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
