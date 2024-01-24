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
- 7404 NOT gate IC
- 7408 AND gate IC
- Wires
- Arduino controller and USB cable


# Breadboard Basics
## Project Step
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
We found out that the top rows are connected to each other horizontally and all the holes in the top row are connected to +5 voltage, and all the holes in the bottom row are connected to the ground. <br />
We verified this by wiring the holes into Logic Indicators so that the top red LED lights up when it is connected to +5 voltage and the bottom green LED lights up when it is connected to the ground.


# Let's Build LED Circuits
### Project Step
### What you need?
- LEDs
- 330 Ohm resistors

### Step 1 - 


## Working with the Arduino
### Step 1 -
For this portion of the lab, it is helpful to first understand what an Arduino is. An Arduino board is an embedded controller that we can use to specify what we would like our circuit to do, as well as let the circuit operate independently. Basically, we are giving the circuit a set of tasks to do autonomously.

### Step 2 - 
- To make use of the Arduino and give it instructions, we used the Arduino IDE (integrated development environment). Here is the link to download that: http://www.arduino.cc/en/software.
- 

<img src="./resources/IMG_0199.JPG" alt="demo 1 pic" height="600"/>






https://github.com/mlcourses/lab-1-blog-post-group2_cs281/assets/108073642/c98ea01f-0c8b-464a-afd8-0b9fb1a6280f




### And Gate
<img src="./and_gate.PNG" alt="demo 1 pic" height="600"/>

### Not Gate
<img src="./not_gate.PNG" alt="demo 1 pic" height="600"/>
The 7404 NOT gate IC is used to take 








```C++
const int P = 13;
const int A = 1000;
const int B = 1000;

void setup() {
  // put your setup code here, to run once:
  pinMode(P, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(P, HIGH);
  delay(A);
  digitalWrite(P, LOW);
  delay(B);
}
```


## Testing

## Conclusion




