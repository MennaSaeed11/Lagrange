# Lagrange Optimization with Mixed Constraints

This repository contains two Jupyter Notebooks related to solving optimization problems using the Lagrange multiplier method.
This approach handles both equality and inequality constraints and demonstrates the use of symbolic computation to address various optimization scenarios.

## Files in this Repository

### 1. **Data Computation Lab 2 (Lagrange).ipynb**
This notebook provides an introductory lab on Lagrange optimization. It covers the basics of the Lagrange multiplier approach and includes practical examples to help users understand how to set up optimization problems with constraints. The lab demonstrates:
- **Defining Objective Functions and Constraints**: Introduces symbolic representation of objective functions and constraints using SymPy.
- **Constructing the Lagrangian**: Shows how to set up the Lagrangian function with equality and inequality constraints.
- **Solving Optimization Problems**: Includes step-by-step examples to guide users through finding optimal solutions.

### 2. **Assignment Notebook**
This notebook builds upon the concepts from the lab and presents a more detailed assignment that explores additional problem-solving techniques. It includes:
- **Advanced Optimization Examples**: Demonstrates how to apply the Lagrange method to more complex functions and constraints.
- **Customized Functionality**: Implements a general function, `lagrange_opt_mixed`, to solve optimization problems with mixed constraints.
- **Example Problems**: Contains sample problems showcasing how to use the function to minimize or maximize objective functions with different sets of constraints.

## Features
- **Symbolic Computation**: Leverages SymPy for symbolic differentiation and function representation.
- **Mixed Constraints**: Handles both equality and inequality constraints.
- **Flexible Optimization**: Allows the user to maximize or minimize objective functions based on their needs.
- **Solution Filtering**: Ensures that solutions satisfy all specified constraints.