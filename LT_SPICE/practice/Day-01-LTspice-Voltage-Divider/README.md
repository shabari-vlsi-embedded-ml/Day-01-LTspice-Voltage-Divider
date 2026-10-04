# Day 1: Simple Voltage Divider in LTspice

## Objective

To simulate a simple resistor voltage divider using DC operating-point analysis in LTspice.

## Circuit Values

- Input voltage: 10 V
- R1: 6 kΩ
- R2: 4 kΩ
- Analysis: DC Operating Point

## Circuit Equation

The output voltage is calculated using:

Vout = Vin × R2 / (R1 + R2)

Therefore:

Vout = 10 × 4k / (6k + 4k)

Vout = 4 V

## Simulation Result

The LTspice simulation produced:

- Input voltage = 10 V
- Output voltage = 4 V
- R1 current = 1 mA
- R2 current = 1 mA

The simulation result matches the theoretical calculation.

## Schematic and Result
## Circuit Schematic

![LTspice voltage divider circuit](C:\Users\hp\Desktop\Projects\LT_SPICE\practice\Day-01-LTspice-Voltage-Divider\sc/voltage-divider-circuit.png)

## Simulation Result

![LTspice voltage divider simulation result](C:\Users\hp\Desktop\Projects\LT_SPICE\practice\Day-01-LTspice-Voltage-Divider\sc/voltage-divider-result.png)

## Files

- `Day1_Voltage_Divider.asc` — LTspice schematic
- `screenshots/voltage-divider-result.png` — Simulation result

## Concepts Learned

- Voltage-divider operation
- DC operating-point analysis
- Ground reference in LTspice
- Measuring node voltage
- Basic Git and GitHub workflow