# Employee Payroll System

A Java-based console application that demonstrates Object-Oriented Programming (OOP) principles including Abstraction, Encapsulation, Inheritance, and Polymorphism.

## Features

- **Abstract Base Class**: `Employee` handles common attributes.
- **Inheritance**: `FullTimeEmployee` and `PartTimeEmployee` extend the base functionality.
- **Polymorphism**: `calculateSalary()` is overridden to handle different salary structures (Monthly vs Hourly).
- **Encapsulation**: Data fields are private and accessed via methods.
- **Management System**: `PayrollSystem` class manages adding, removing, and listing employees using an `ArrayList`.

## How to Run

1. Compile the files:
   ```bash
   javac src/*.java