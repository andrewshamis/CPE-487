# Lab 3

## VHDL Files
Ball: [ball.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/ball.vhd)

Clocking Wizard: [clk_wiz_0.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/clk_wiz_0.vhd)

Clocking Wizard Architecture: [clk_wiz_0_clk_wiz.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/clk_wiz_0_clk_wiz.vhd)

VGA Sync: [vga_sync.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/vga_sync.vhd)

VGA Top: [vga_top.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/vga_top.vhd)


## Constraint Files:
Bouncing Ball: [vga_top.xdc](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/vga_top.xdc)

## Required Hardware:
- Monitor with VGA connection or HDMI
- VGA to HDMI adapter (optional)

## Project 1: Bouncing Ball

Below is the implemented design of the circuit in Vivado.

![Implemented Design](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/Implemented_Design.jpg)

The video shows a red square bouncing up and down across a monitor.

https://user-images.githubusercontent.com/78375489/160260020-3e26223f-0859-4960-a2e8-7b980bfbf39c.mp4

## Project 2: Modified Bouncing Ball

The updated version of the code has changed the shape and color of the ball, as well as the directions that it can bounce in (now vertical and horizontal)

https://user-images.githubusercontent.com/78375489/160260046-c3176b9a-0d10-435d-a7e8-c35a74963ce8.mp4

# Lab 6

## VHDL Files

### Video Game Pong

- Analog to Digital Converter: [adc_if.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/adc_if.vhd)

- Bat and Ball: [bat_n_ball.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/bat_n_ball.vhd)

- Clocking Wizard: [clk_wiz_0.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/clk_wiz_0.vhd)

- Clocking Wizard Architecture: [clk_wiz_0_clk_wiz](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/clk_wiz_0_clk_wiz.vhd)

- PONG: [pong.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/pong.vhd)

- VGA Sync: [vga_sync](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/vga_sync.vhd)


### Modified Video Game Pong

- Bat and Ball: [batt_n_ball_1.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/bat_n_ball_1.vhd)

- LED Decoder: [leddec16.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/leddec16.vhd)

- PONG: [pong_1.vhd](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/pong_1.vhd)


## Constraint Files:
- PONG: [pong.xdc](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/pong.xdc)
- Modified PONG: [pong_1.xdc](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/pong_1.xdc)

## Required Hardware:
- Monitor with VGA connection or HDMI
- VGA to HDMI adapter (optional)

## Project 1: Pong Game

Below is the implemented design of the circuit in Vivado.

![Implemented Design](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/Lab_6_Implemented_Design_3.jpg)

The video shows a game of pong that requires the use of a potentiometer to move a blue base across the screen and bounce a red ball

https://user-images.githubusercontent.com/78375489/160262570-e098638f-275f-4229-8745-6dd64a518bda.mp4

## Project 2: Modified Pong Game

The updated version of the code changes the thickness of the base, adds a counter for the number of hits every game, and decreases the width of the base by one pixel after every hit.

![Modified Implemented Design](https://github.com/andrewshamis/CPE-487/blob/main/Homework_5/Lab_6_Implemented_Design_4.jpg)



  
