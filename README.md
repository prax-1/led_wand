# LED Chaser Wand

This repository contains the files and documentation for the **LED Chaser Wand** project. The wand is powered by a single AA battery and uses a 555 timer, SN74H counter, and CD74HC138 decoder to create a chaser effect with 8 LEDs arranged on a PCB shaped like a wand.

## Project Overview

### Components Used
- **Power Source:** AA battery
- **Clock Generator:** 555 Timer IC
- **Counter:** SN74H
- **Decoder:** CD74HC138
- **LEDs:** 8 standard LEDs
- **PCB:** Custom designed in the shape of a wand

### Circuit Design
- The 555 timer is configured to generate a clock pulse.
- The SN74H counter increments with each clock pulse.
- The CD74HC138 decoder takes the counter output and drives one of the 8 LEDs in sequence.
- This setup creates a chaser effect where LEDs light up one after another.

## Project Files

### Hardware
- `PCB_Layout.png`: Layout of the PCB designed for the project.
- `Schematic.png`: Circuit schematic showing the connections between components.
- `Components_List.txt`: Detailed list of all components used.

### Source Code
- `src/code.ino`: Arduino-compatible code to simulate the chaser effect (optional if using microcontroller).

### Images
- `wand_front_view.jpg`: Front view of the assembled wand.
- `wand_back_view.jpg`: Back view of the assembled wand.
- `led_chaser_effect.gif`: Animated GIF showing the chaser effect in action.

## Assembly Instructions
1. **Prepare Components:** Gather all the components listed in `Components_List.txt`.
2. **Assemble the Circuit:** Follow the schematic in `Schematic.png` to solder components onto the PCB.
3. **Power the Wand:** Insert the AA battery to power the circuit.
4. **Enjoy the Effect:** Watch as the LEDs create a chaser effect.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contribution
Feel free to fork this repository and contribute by submitting issues or pull requests.

## Contact
For any questions or suggestions, please contact [Prakhar] at [Email](mailto:prakhargupta1811@gmail.com).
