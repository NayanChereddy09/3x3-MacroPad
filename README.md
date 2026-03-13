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
| Component | Quantity |Price (CAD)| Link |
|----------|----------|-----|------|
| XIAO RP2040 | 1 |6.76| [https://www.seeedstudio.com](https://www.digikey.ca/en/products/detail/seeed-technology-co-ltd/102010428/14672129?gclsrc=aw.ds&gad_source=4&gad_campaignid=23152963569&gbraid=0AAAAADrbLliMt5VgMeGPaIKlgcr2Q90fY&gclid=CjwKCAjwyMnNBhBNEiwA-Kcguwrg1UbtNIWS-P4FAAAyMwybB_aWCFUh-iDmOwp-9kJHo128SbXdAxoC5JgQAvD_BwE) |
| Switches | 9 |8.89|https://www.amazon.ca/Switches-Mechanical-Keyboard-Mounted-Replacement/dp/B0C6FH6XQ7/ref=sr_1_1?crid=38CW69GPF8ZTK&dib=eyJ2IjoiMSJ9.gDDEQemwgyX_4Vj4VuR1aBpI1heONHtJbnLXmt0pJpzFKpCB2n2V8i0gYCoUe0aqaWEM2j4HSuP8CIm5VOC60iTwoxWRKPpGjG_BJ5zAh8Bzbo6whe0h02ZNaezuxDbT7hBEZ1YZOoWVCUfleT1NSjtqJcb81PlimzaSGx_bPr-8rXzpsUXTrkOb1IfkNAhECfPloiA7PgHfldtqIDsJllxG63iTDPacrd0RyTM-5pqfjy00iBLh2w-WybO56YL31iAtbV2Y8TvyEqC2udhWs6cEfSjfufZ34F1_BNdKr9Y.Bnsgtc34rMx7zjjuMh87nFle-BU4BoW1TpSmIbQwDu0&dib_tag=se&keywords=9x+Cherry+MX+Switches&qid=1773369800&s=industrial&sprefix=9x+cherry+mx+switches%2Cindustrial%2C137&sr=1-1  |
|Keycaps | 9 |13.50|https://www.amazon.ca/Mechkeeb-Profile-Switches-Keyboard-Replacement/dp/B0BWDTBF1L/ref=sr_1_9?dib=eyJ2IjoiMSJ9.vLZHqW7v1byZDztT7uic4RNnGpDhDmTOYn12RkpMr22X2om01iwAtvLOaJZHBKRfAE7DxGzd2GLbXxV8l2s0mlzYR1cLenr13OKDLtwcj5xKt-XE1ULeF7AoppwTJDtgk-JOhe43i3g6vD-JBoCzBD4yfSrRescVXXnhVxtay0GmCLNpiuM8qdOnQJr3HMr4ZStUmbkACsz9cC99YZOc4MryjE0xVRK7Ff6-1smv1NZpfrb4mVPAa7q5o0XEHinFxVGJFu88FedVWPs9htQKqeSGFefirzkaHu5nc2lOjKQ.O8AQWRd1pZ3tRoIpiLvLoZu1Tn-UVn5POOrxSPTvyWM&dib_tag=se&keywords=Blank%2BKeycaps&qid=1773370038&sr=8-9&th=1| 
| Diodes | 9 |1.26 (0.14 each) | https://www.digikey.ca/en/products/detail/onsemi/1N4148/458603 |
| 0.91" 128x32 OLED Display | 1 | 19.99| https://www.amazon.ca/128x32-SSD1306-Consumption-Display-Arduino/dp/B07PDFCVXL |
| M3x16mm Screws | 4 |7.96 (1.99 each) | https://www.canadiantire.ca/en/pdp/hillman-philips-pan-head-machine-screw-m3-50-x-16-mm-0612155p.html#store=674|
| M3x5x4mm Heatset Inserts | 4 |10.99 | https://www.amazon.ca/HANGLIFE-Heat-Set-Threaded-Printing-Components/dp/B0CS6VZYL8/ref=sr_1_6?crid=EW7LJL1KR51M&dib=eyJ2IjoiMSJ9.cxQgZLlRRbKSwCCORB3HdUv1wvlNI-g8OEJd1Gu5GP9SEO7yPCWcU2OmdrlRRSyMhW9UbiWO1dIkx4C1Fu32ofoJ_aq3AHX_v_ZvZk-5RhZCHNdGdEuYjVugN9duHbruX4eFpzpvan1sQSgvzyYcZkWrvd4BhCQYSpIySM-uG7mxGKymo4rGg9slaS_a-BtMR41aLZhwf-2ut6srBcoeR0HfqyG5svNrHudQ7tp9jV8NTbzNjZXWrFWGMoC23gnZv6PCOLAcI1Q_qBTqz2tqgIWRI-D2GWCwbTUQkW56sBM.LsZMgfr5YmpYX-NCRVd_PZ5zqXHvR0eP7PGamzMy5E4&dib_tag=se&keywords=M3x5x4mm%2BHeatset%2BInserts&qid=1773371383&s=industrial&sprefix=m3x5x4mm%2Bheatset%2Binserts%2Cindustrial%2C170&sr=1-6&th=1|
| PCB JLC | 1 | 3.5|https://cart.jlcpcb.com/quote?stencilLayer=2&stencilWidth=100&stencilLength=100&stencilCounts=5&plateType=1&spm=Jlcpcb.Homepage.1010|
|3d Printed Case| 1 | 6.46| https://jlc3dp.com/3d-printing-quote|

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

# License

This project is open-source and available for modification and improvement.
