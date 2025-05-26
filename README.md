# Traffic-Light-Controller
Microcontroller-based traffic light controller PCB using ATmega328P, RGB LEDs, and a two-digit countdown timer with SSDs. Includes onboard 12V to 5V power regulation using LM7805. Designed as the final project for a PCB design course.

## Project Details

**Project Name:** Traffic Light Controller

**Software Used:**   Altium Designer

## Project Description

Designed a microcontroller-based traffic signal controller PCB featuring:

- **ATmega328P** as the microcontroller
- **RGB LEDs** as traffic lights (Red, Yellow, Green)
- Two **7-segment displays (SSD)** with driver ICs to show a two-digit countdown timer
- Power supply section converting **12V DC to 5V DC** using an **LM7805 voltage regulator**
- Complete **schematic and PCB layout** created using provided component libraries

The controller manages traffic signals and displays a countdown timer to indicate the remaining time for each light.

## Block Diagram
![Final_Project_-_Block_Diagram](https://github.com/user-attachments/assets/17f82189-f017-4f70-8b54-64779510ad27)


*Block diagram showing the overall system architecture*

## Schematic

![KC_Traffic Light Controller_Schematic](https://github.com/user-attachments/assets/384ee594-f210-44ba-a7ce-50f72f1fa528)


## PCB Layout
![KC_Traffic Light Controller_Layout](https://github.com/user-attachments/assets/eabb891f-f094-4777-a9a1-f69b5c397141)

## Manufacturing Tab

![KC_Traffic Light Controller_manufacturing tab](https://github.com/user-attachments/assets/09c8fdb0-ba58-4d2f-a38a-a8e7ed7eaf6e)


## Power Supply

The circuit includes a power supply module that steps down a **12V DC input** to a regulated **5V DC output** using the **LM7805 voltage regulator**, ensuring a stable power source for the microcontroller and peripheral components.

## Features

- Microcontroller-controlled traffic lights using RGB LEDs
- Two-digit countdown timer visible on SSDs
- On board 12V to 5V regulated power supply using LM7805

## Tools and Components

- **Microcontroller:** ATmega328P
- **Display:** Two 7-segment displays with driver ICs
- **Traffic Light:** RGB LEDs
- **Power Supply:** LM7805 voltage regulator (12V to 5V)
- Component libraries provided by the course mentor

## Project Files

- `Schematic/Traffic Light Controller.sch` — Circuit diagrams  
- `PCB Layout/Traffic Light Controller.brd` — PCB design layout  
- `CAM Outputs/Gerber Files` — Manufacturing files for PCB fabrication  
- `BOM` — Bill of Materials listing all components   
- `Images` — Board photos and design previews  
- `Libraries` — Libraries were provided by mentor

## Credits

This project was developed as part of a final project of a course from [Internshala](https://internshala.com/).  
