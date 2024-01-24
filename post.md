# Lab 1: Let's learn some hardware with PB-503 and Arduino

Please write a blog post describing your lab here.

This is just an example of how you might structure your blog post, feel free to edit as you wish. For example, you might divide the lab into different sections each with their own intro, instructions, results, and takeaways. Please see the rubric for details on how the post will be evaluated.

# Overview and Motivation
Welcome to the Lab 01 of CS281: Introduction to Computer Systems! 
This lab serves as your gateway into the world of hardware and embedded systems. The lab will take you through the intricacies of the PB-503 breadboard prototyping stations and the Arduino microcontroller system. By the end of this lab, you'll be adept at working with essential circuit components like LEDs, resistors, and logic gates, and you'll understand how to interpret IC data sheets—an invaluable skill in the realm of computer systems.


# Objectives of the Lab
1. Familiarize yourself with the PB-503 breadboard and Arduino microcontroller.
2. Understand and construct basic circuits using LEDs, resistors, and integrated circuit chips.
3. Develop the ability to read and interpret IC data sheets.
4. Gain hands-on experience in controlling circuits with the Arduino.
 
# Materials
- PB-503 breadboard prototyping station (integrated device with a number of electrical components like switches)
- Arduino kit
- LEDs
- 330 Ohm resistors
- Logic probes
- 7404 OR gate IC
- 7408 AND gate IC
- Wires
- Arduino controller and USB cable


# Project Steps
## Breadboard Basics
### Step 1 - Explore PB-503:
Look for the integrated components like switches, LEDs, power supplies, and the function generator.
![Alternate image text](./resources/IMG_0195.JPG)

### Step 2 - Powering the Breadboard: 
Learn to power up the breadboard correctly, focusing on the +5 Volts power supply and the Ground connection. 
Firstly, you need to connect the red wire from the power supply to the top row and the black wire from the ground to the top second row of the breadboard.
#### Note: DO NOT hook a wire to any of the other voltages since the circuits we use all run on 5 volts.
#### Note : Always turn off the breadboard power when you are now

### Step 3 - Using Logic Indicators: 
eight of them on the right-hand side, and you can use them to determine HIGH or LOW voltage from a location on the breadboard by connecting a wire from the location of interest to one of the eight Logic Indicators. Get a long single wire that is long enough to stretch across the board.
Use the  Logic Indicators (eight of them on the right-hand side) to determine HIGH or LOW voltage from a location on the breadboard by connecting a wire and understand the voltage levels at different points on the breadboard. Through this step you can verify your circuit connections for the rows and colums.<br />
<br />
#### Note : The double check your connections against your circuit diagram before turning the power on.
<br />
High:
![Alternate image text](./resources/IMG_0196.JPG)
<br />
<br />
Ground:
![Alternate image text](./resources/IMG_0197.JPG)

### What We Learned: 
We found out that top rows is connected to each other horizontally and all the holes are top rows is connected to +5 voltage and all the holes in the bottom rows are connected to the ground. <br />
We varified this by wiring the holes into Logic Indicators that top red LED light up when it is connected to +5 voltage and bottom green LED light up when it is connected to the ground.


## Let's Build LED Circuits
### Step 1 - 

![Alternate image text](./resources/IMG_0199.JPG)




### And Gate
![Alternate image text](./and_gate.PNG)

### Not Gate
![Alternate image text](./not_gate.PNG)









## Testing

## Conclusion




