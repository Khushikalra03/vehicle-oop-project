# Vehicle Management System (OOP Project)

This project demonstrates the concepts of **Object-Oriented Programming (OOP)** in Python using an abstract class and multiple subclasses.  
It models different types of vehicles and shows how abstraction, inheritance, and method overriding work together.

---

## 🚗 Project Overview

The project includes:

- An **abstract class** `Vehicle`
- Three **subclasses**:
  - `Car`
  - `Truck`
  - `Motorcycle`
- Implementation of:
  - Abstract methods (`start_engine`, `stop_engine`, `calculate_fuel_efficiency`, `get_details`)
  - Property getters & setters
  - Polymorphism through a loop that handles all vehicle objects the same way

Each vehicle type provides its own version of engine behavior, fuel efficiency, and details.

## 🧠 Concepts Demonstrated

- **Abstraction**  
  `Vehicle` is an abstract base class with abstract methods.

- **Inheritance**  
  `Car`, `Truck`, and `Motorcycle` inherit from `Vehicle`.

- **Encapsulation**  
  Private attributes (`__brand`, `__model`, etc.) are accessed using `@property`.

- **Polymorphism**  
  A list of vehicles is iterated and each object responds with its own method implementation.

This is a simple demonstration of class hierarchy and method overriding in Python.
