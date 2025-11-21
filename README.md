# Java Employee Payroll System 👨‍💻

A robust console-based application designed to demonstrate core **Object-Oriented Programming (OOP)** principles in Java. This system manages employee records, distinguishing between full-time and part-time staff, and calculates salaries based on specific criteria.

## 🚀 Features

* **Add Employees:** Supports adding both Full-Time and Part-Time employees.
* **Remove Employees:** Delete employees from the system using their unique ID.
* **View All Employees:** Display a list of all current employees with their details.
* **Salary Calculation:** Automatically calculates salary based on employment type (Monthly fixed vs. Hourly rate).

## 🧠 OOP Concepts Implemented

This project is a practical implementation of the four pillars of OOP:

1.  **Abstraction** 🛡️
    * Implemented via the `Employee` abstract class.
    * The `calculateSalary()` method is abstract, forcing subclasses to provide their own implementation logic.

2.  **Inheritance** 🧬
    * `FullTimeEmployee` and `PartTimeEmployee` classes inherit common attributes (name, id) from the parent `Employee` class to avoid code duplication.

3.  **Polymorphism** 🎭
    * **Method Overriding:** Both subclasses override the `calculateSalary()` method to calculate wages differently.
    * The `toString()` method is overridden to provide a custom string representation of employee objects.

4.  **Encapsulation** 💊
    * All data fields (e.g., `name`, `id`, `salary`) are `private`.
    * Access is controlled via public Constructor and Getter methods to ensure data security.

## 📂 Project Structure

```text
EmployeePayrollSystem/
├── src/
│   ├── Employee.java           # Abstract base class
│   ├── FullTimeEmployee.java   # Subclass for fixed salary
│   ├── PartTimeEmployee.java   # Subclass for hourly wages
│   ├── PayrollSystem.java      # Manages the list of employees
│   └── Main.java               # Entry point/Execution logic
├── .gitignore                  # Git ignore file
└── README.md                   # Project documentation
