# Digital Thermometer: My Electronics Journey

My journey to build a digital thermometer, step by step: circuit
simulation, embedded C firmware, and PCB design.

I am a first-year electronics student. Each step below contains a
report with hand calculations, LTspice simulations, and what I learned.

## Goal

Design and build a digital thermometer: a temperature sensor, an
analog amplifier and filter, an ADC, firmware in C, and a PCB.

## Progress

| Step | Topic | Status |
| --- | --- | --- |
| [Step 1](step01) | Voltage divider and current divider | Done |
| Step 2 | RC circuit and filters | In progress |
| Step 3 | Diode, LED and transistor as a switch | Planned |
| Step 4 | Op-amp circuits (LM358) | Planned |
| Step 5-8 | Embedded C: GPIO, PWM, interrupts, ADC, UART | Planned |
| Step 9-12 | KiCad schematic, PCB layout, final report | Planned |

## Tools

- LTspice (circuit simulation)
- LaTeX / Overleaf (reports)
- KiCad (PCB design, later)
- Wokwi (firmware simulation, later)

## Step 1 summary

- Voltage divider: hand calculation matches LTspice (2.878 V vs 2.87755 V).
- A 1 kΩ load drops the output to 0.686 V, because the load must be much
  larger than R2 to keep the divider accurate.
- Current divider: I2 = 3.27 mA and I3 = 2.18 mA, verified with KCL.

## Author

Islam Kacem
