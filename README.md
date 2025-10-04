# DrivingStimulationLab-Project

# Driving Simulation Lab

## Overview
`DrivingSimulationLab` is a simple **text-based car simulation** program written in Java.  
It allows the user to interact with a virtual car by performing actions such as turning the engine on/off, changing gears, accelerating, braking, and exiting the simulation.

The program demonstrates basic **Java programming concepts** including loops, conditionals, methods, and user input handling.

---

## Features

1. **Engine Control**
   - Turn the engine ON or OFF.
   - When turned OFF, the car stops and gear resets to Park (`P`).

2. **Gear Control**
   - Change gears between Park (`P`), Drive (`D`), and Reverse (`R`).
   - Gear can only be changed if the engine is ON.

3. **Acceleration**
   - Increase the car speed by 10 units at a time.
   - Can only accelerate if the engine is ON and gear is not Park (`P`).

4. **Braking**
   - Decrease the car speed by 5 units at a time.
   - If speed is less than 5, braking will stop the car completely.
   - Braking is only possible if the engine is ON.

5. **Exit**
   - Exit the simulation at any time.

---

## How to Run

1. Make sure you have **Java installed** on your system (JDK 8 or higher).

2. Compile the Java program:  javac DrivingSimulationLab.java

3. Run the program: java DrivingSimulationLab

4. Follow the menu prompts and interact with the simulation. Example run:

   ------ Car Dashboard ------
Speed: 0
Engine: Off
Gear: P
Menu:
1. Turn on/off the engine
2. Change gear (P, D, R)
3. Accelerate
4. Brake
5. Exit
Enter your choice: 1
Engine turned ON.

Enter your choice: 2
Enter gear (P/D/R): D
Gear changed to D

Enter your choice: 3
Accelerated! Current speed: 10

Enter your choice: 4
Braked! Current speed: 5

Enter your choice: 5
Exiting the driving simulation. Goodbye!


## Learning Outcome
From this assignment, I learned:

- How to structure a Java program using classes and methods.  
- How to accept and validate user input with `Scanner`.  
- How to implement conditional logic using `if-else` and `switch-case`.  
- How to use loops to create an interactive simulation.  
- How to simulate real-world processes like car controls using code.  

This assignment helped me understand the basics of **object-oriented programming** and **interactive console applications** in Java.

---




4. Run the prog
   javac DrivingSimulationLab.java
