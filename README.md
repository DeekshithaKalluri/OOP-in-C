# Object-Oriented Programming in C - Person & Employee System

## Overview

This project simulates object-oriented principles in the C programming language using structures and function pointers. It defines a base type `Person` and an extended type `Employee`, demonstrating how C can emulate class-like behavior, including inheritance and dynamic dispatch.

## Features

- Create and manage `Person` and `Employee` objects
- Encapsulate data using structures
- Use function pointers to simulate polymorphism
- Dynamic memory allocation with cleanup

## File Structure

- `main.c`: Demonstrates usage by creating and displaying `Person` and `Employee` objects.
- `Person.h` / `Person.c`: Defines the base `Person` type with `firstName`, `lastName`, and method-like function pointers for display and cleanup.
- `Employee.h` / `Employee.c`: Defines the `Employee` type as an extension of `Person`, with additional fields such as `company`, `department`, and `salary`.
