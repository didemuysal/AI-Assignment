# Digital Logic Circuit Analysis and Implementation
This repository contains the solution to a digital logic assignment. The project involves analyzing a given logic circuit, deriving its Boolean expression, completing its truth table, and implementing a functional simulation in Python.

Project Overview
The project is broken down into three main tasks based on a logical circuit with four inputs (p, q, r, w) and one output (z).

Task 1: Logical Expression Derivation
The first task was to derive the Boolean algebra expression for the circuit diagram. The step-by-step derivation resulted in the following logical expression for the output z:

z = ¬p ⨁ ((((p ∨ q) ⨁ r) ∨ (¬(r ∧ w))) ⨁ w)

The circuit consists of 8 individual logic gates: 3 XOR gates, 2 NOT gates, 2 OR gates, and 1 AND gate.

Task 2: Truth Table Completion
A truth table for the 4-input, 16-combination circuit was completed based on the derived logical expression. The output z was calculated for each possible combination of the binary inputs p, q, r, and w.

Task 3: Python Implementation
A Python script was created to simulate the behavior of the logical circuit. The key features of the implementation are:

Logic Gate Functions: Individual functions for basic logic gates (AND, OR, NOT, XOR).

Circuit Simulation: A main function Logical_Circuit(p,q,r,w) that implements the full logical expression from Task 1 by combining the gate functions.

User Input: The program prompts the user to enter binary values (0 or 1) for the inputs p, q, r, and w, and it calculates and displays the corresponding output z, effectively validating the truth table.
