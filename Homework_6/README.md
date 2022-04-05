# Lab 4: Hex Calculator

## VHDL Files

### Calculator
- Hex Calculator: [hexcalc.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/hexcalc.vhd)
- Keypad: [keypad.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/keypad.vhd)
- LED Decorder (16-bit): [leddec16.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/leddec16.vhd)

### Modified Calculator
- Hex Calculator: [hexcalc_1.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/leddec16.vhd)
- Keypad: [keypad.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/keypad.vhd)
- LED Decorder (16-bit): [leddec16_1.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/leddec_1.vhd)

## Constraint Files:
- Hex Calculator: [hexcalc.xdc](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/hexcalc.xdc)
- Modified Hex Calculator: [hexcalc_1.xdc](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/hexcalc_1.xdc)

## Required Hardware:
- Pmod Keypad
- Pin Connector

## Project 1: Hex Calculator

Below is the implemented design of the circuit in Vivado.

![Implemented_Design](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/Lab_4_Implemented_Design.jpg)

![Hex Calculator](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/IMG_docpqs.gif)


## Project 2: Modified Hex Calculator

The modified hexcalc files serve to make the following changes:

- Leading zero suppression (ledded16_1.vhd)
- subtraction operations (hexcalc_1.vhd)
- The BTND (P18) button for substraction (hexcalc_1.xdc)

Below is an implemented design of the updated circuit in Vivado.

![Modified_Implemented_Design](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/Lab_4_Implemented_Design_1.jpg)

![Modified Hex Calculator](https://github.com/andrewshamis/CPE-487/blob/main/Homework_6/IMG_sm4nim.gif)
