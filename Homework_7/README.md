# Lab 5: DAC Siren

## VHDL Files

### DAC Siren
- Digital to Analog Converter: [dac_if.vhd]()
- Siren: [siren.vhd]()
- Tone: [tone.vhd]()
- Wail: [wail.vhd]()

### Modified DAC Siren
- Digital to Analog Converter: [dac_if.vhd]()
- Siren: [siren.vhd]()
- Tone: [tone.vhd]()
- Wail: [wail.vhd]()

## Constraint Files:
- Siren: [siren.xdc]()
- Modified Siren: [siren_1.xdc]()

## Required Hardware:
- Pmod I2S
- 3.5mm Speaker

## Project 1: DAC Siren

Below is the implemented design of the circuit in Vivado.

![Implemented_Design]()

![DAC Siren]()


## Project 2: Modified DAC Siren

The modified hexcalc files serve to make the following changes:

- tone_1.vhd: tone_select, btn_press, data_sq

- wail_1.vhd: btn_press

- siren_1.vhd: left and right channels

- siren_1.xdc: BTNU (M18), SW0-SW7

Below is an implemented design of the updated circuit in Vivado.

![Modified_Implemented_Design]()

![Modified Hex Calculator]()
