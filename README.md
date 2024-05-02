# Arduino Dice Simulator

***This Arduino project simulates rolling a dice using 6 LEDs, a tilt sensor to trigger the simulation, an ATtiny chip, and a CR2032 3V battery. When the tilt sensor detects a triggering motion, the LEDs display a random dice face for a short duration.***

## Components Used
- **ATtiny Chip :** Controls the operation of the simulation.
- **6 LEDs :** Represent the six faces of a dice.
- **Tilt Sensor :** Triggers the simulation when it detects motion.
- **CR 2032 3V Battery :** Powers the circuit.

## Libraries Used
*None*

## How It Works
1. **Initialization :** The pins for LEDs and the tilt sensor are initialized in the setup phase.
2. **Simulation Triggering :** When the tilt sensor detects a triggering motion, the simulation is initiated.
3. **Randomization :** A pseudo-random number generator creates a new dice face each time, ensuring unpredictability.
4. **LED Display :** The generated dice face is displayed by lighting up the corresponding LEDs.
5. **Repitition :** The face of the dice is displayed multiple times in quick succession for visual effect.
6. **Avoiding Repeats :** The system ensures that the same dice face is not displayed consecutively to prevent cheating.
7. **Power Management :** The system is designed to minimize power consumption to maximize battery life.

## Usage
- Place the device on a flat surface.
- Tilt the device to trigger the simulation.
- LEDs will light up to display the result of the simulated dice roll.
- The result will be displayed multiple times before the LEDs turn off.

## Circuit Diagram
![](https://i.ibb.co/cx6J61Q/arduino-dice.jpg)

## Note
- Ensure proper connections and component compatibility before assembling the circuit.
- Cutomize the code or hardware configuration as needed for specific requirements or enhancements.

[**click to watch**](https://youtu.be/Ou50MMpRY1k)
