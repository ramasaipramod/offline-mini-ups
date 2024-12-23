# Offline Mini UPS

This project involves designing a 3-section Offline Mini UPS with the following functionalities:

1. **Inverter Section and Mains-Inverter Changeover Section**  
   Ensures power transition between mains and inverter.

2. **Oscillator Section**  
   Generates the required oscillation for the offline UPS.

3. **Battery Status Indicator Section**  
   Displays the charge status of the connected 12V battery.

## Files in the Repository

### EAGLE Files
- **`EP Project.brd`**: PCB layout design.  
- **`EP Project.sch`**: Schematic diagram of the circuit.

### EasyEDA Files
- **`PCB.json`**: PCB design in JSON format.  
- **`info`**: Project metadata.  
- **`project.json`**: Full project configuration file.

## Components Used
- **Passive Components**: Resistors and capacitors with various values.  
- **Integrated Circuits**: Dual JK Flip-Flop, 555 Timer.  
- **Transistors**: NPN and PNP types.  
- **Diodes**: Rectifier diodes, Zener diodes.  
- **Other Components**:  
  - LED, neon lamp.  
  - Transformer, relay, and 12V battery.  
  - 2-pin connector and ON/OFF switch.
