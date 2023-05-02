# Rumor Distribution Cellular Automaton

This project creates a cellular automaton that allows you to analyze the distribution of a rumor in a network of people.

## Usage

The final program can be used with the `main.exe` file. After double-clicking on the file, another screen should appear, and the simulation should begin. 

First, the user can choose the desired parameters:
- "P" is the population density
- "L" is the waiting time between spreading rumors
- S1 is the percentage of people who believe every rumor
- S2 the percentage of people who believe the rumor they hear with a probability of 2/3
- S3 the percentage of people who believe the rumor they heard with a probability of 1/3
- S4 the percentage of people who don't believe any rumors

The parameters P and S's are a number between 0 and 1 inclusive, and the parameter L is an integer.

After entering the parameters, press start to activate the simulation. The screen should display a 100x100 grid of squares, where each square represents a potential person. Green squares represent people who did not hear the rumor, and red squares represent people who heard the rumor (white squares are not people). On the left side of the screen, you can see the parameters selected for the simulation. Below the simulation, you can see the percentage of people who were exposed to the rumor out of the total number of people and the number of generations that have passed.

## Python files
The Python files that were used to create the program are also attached to this repository.
