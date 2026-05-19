# Exercise 2 — Arduino Alarm Clock

## Overview
This exercise introduced the fundamentals of Arduino-based prototyping through the development of a functional alarm clock system using multiple electronic components and communication interfaces. The objective of the exercise was to understand how microcontrollers interact with external hardware devices such as buzzers, LCD displays, real-time clock (RTC) modules, and push buttons to create an interactive embedded system.

Unlike the previous exercise, which focused mainly on passive electrical circuits and transistor-based switching, this exercise introduced programmable electronics using the Arduino Uno platform. Through assembling and testing different sub-circuits, I learned how software and hardware work together in embedded systems.

The exercise involved building and testing individual sub-circuits step-by-step before integrating them into a complete alarm clock system. Throughout the process, the circuits were assembled, programmed, debugged, and tested using the Arduino IDE, breadboard prototyping, and serial communication tools.

The following sections document the assembly process, observations, programming concepts, and reflections for each task.


---

# Sub-circuit 1 – Connecting the buzzer

## Objective
The objective of this task was to understand how a buzzer can be controlled using an Arduino Uno and digital output signals. This task introduced the basics of Arduino programming, digital HIGH and LOW states, and simple actuator control using a programmable microcontroller.

## Components Required
- Arduino Uno
- Buzzer
- Resistor
- Breadboard
- Male-male jumper wires

## Circuit Assembly
The circuit was assembled according to the provided schematic by connecting the buzzer to one of the Arduino digital output pins through a resistor. The Arduino was powered using the USB connection from the computer.

After assembling the circuit, the provided `buzzer_test.ino` sketch was uploaded using the Arduino IDE. Different delay values and timing sequences were tested to observe how the buzzer behaviour changes depending on the programmed delays.

Initially, understanding the Arduino pin configuration and uploading code to the board required careful setup and troubleshooting before the buzzer operated correctly.

<p align="center">
  <img src="images/buzzer-circuit.jpg" width="600">
</p>

<p align="center">
  <em>
    Figure 1: Testing the buzzer circuit using Arduino Uno.
  </em>
</p>

## Observations
After uploading the test program, the buzzer successfully produced sound according to the programmed timing sequence. By modifying the delay values in the code, different beep intervals and sound patterns were observed.

It was observed that the Arduino digital output pins can directly control simple electronic actuators such as buzzers through HIGH and LOW output signals. The task also demonstrated how software timing directly influences hardware behaviour in embedded systems.

During testing, changing the delay duration produced noticeable differences in the speed and rhythm of the buzzer sound. The recorded video captured the buzzer behaviour while running the provided test code.

https://github.com/user-attachments/assets/068e5b70-0146-4c19-aabb-8d2d0d234a65

**Video 1:** Demonstration of buzzer behaviour using different delay timings in the provided Arduino test program.

## Reflection
This task provided my first practical experience with Arduino programming and digital actuator control. It also helped me understand how electronic components can be controlled programmatically using simple Arduino code and digital output signals.

Through testing different delay values and observing the buzzer behaviour, I also gained a better understanding of how timing functions influence hardware operation in embedded systems.
