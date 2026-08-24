# STM32C011F6-Dev-Board
A development board for the STM32C011F6 for use on a breadboard. It has power regulation, SWD programming capabilities, a reset button, and power LED. All GPIO pins are put to a broken out header pin. Resistors are added on SWD pins to improve signal integrety, allowing for more versatility in its usage.

The input voltage pin accepts between 3.3 and 15V, and the microcontroller can run on an input voltage as low as 2V4. The microcontroller runs on 3V3 GPIO signals and power under optimal conditions. Across all output pins and power pins, the total power draw through the VCC pin is 3.3 Watts, and the total current draw out of any individual pin is 20mA.

This board is 0.84"x1.14", and fits on a breadboard when male pin headers are soldered onto the board. 

Below is the schematic for the dev board, created in KiCad 9.0

<img width="1156" height="802" alt="STM32C011F6_Schematic" src="https://github.com/user-attachments/assets/4315187d-1520-4c2f-ad4a-c2f763ae1468" />

Fully rendered image of the PCB design

<img width="910" height="1226" alt="STM32C011F6_PCB_Picture" src="https://github.com/user-attachments/assets/46f8cb7a-d5ee-48a7-aaee-856d7cb0c3bf" />

PCB design file

<img width="1050" height="1434" alt="PCB_Design" src="https://github.com/user-attachments/assets/e51e042f-4ac6-4af1-b755-7c2532b2c2cd" />

