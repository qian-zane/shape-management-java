# Shape Management System

A Java application developed as part of the Object-Oriented Programming module at the University of York.

The project demonstrates core object-oriented programming principles through a system for creating and managing geometric shapes.

## Features

- Supports circles, rectangles, squares and triangles
- Calculates area and perimeter for different shapes
- Translates shapes using coordinate positions
- Scales shapes
- Manages multiple shapes through a central ShapeList
- Uses an abstract Shape superclass with specialised subclasses

## Object-Oriented Design

The project applies:

- Abstraction
- Inheritance
- Encapsulation
- Polymorphism
- Method overriding

`Shape` provides the common abstraction for geometric objects, while classes such as `Circle`, `Rectangle`, `Square` and `Triangle` implement shape-specific behaviour.

## Technologies

- Java
- Object-Oriented Programming
- ArrayList
- UML-based class design

## Project Structure

- `Shape.java` – abstract base class
- `Coordinates.java` – coordinate representation and transformations
- `Circle.java` – circle implementation
- `Rectangle.java` – rectangle implementation
- `Square.java` – square implementation
- `Triangle.java` – triangle implementation
- `ShapeList.java` – manages collections of shapes
- `Main.java` – application entry point

## What I Learned

This project helped me develop a stronger understanding of designing Java applications using object-oriented principles, organising related classes, and implementing shared and specialised behaviour through inheritance and polymorphism.
