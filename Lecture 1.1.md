## OOP: Classes

- A template or blueprint from which instances of objects may be created.
- Creation of an instance is called **instantiation**_**.**_

## OOP: Objects

- What is created when a class is instanced.
- Each object is an **instance of a class** that is _distinct._
- Has its **own copy of attributes.**
- Can act in the same way the class was designed.

## Example of Classes and Objects

Say we have a `human` class and it has an age attribute. We can instance many `human` objects with difference ages.

`human(int age)`

        -> `human(10)`

        -> `human(12)`

        -> `human(20)`

Key points:

- Each instantiation is distinct from another object.
- Each instantiation has its own attributes (the `age`).

## Principles of OOP

1. **Encapsulation**. A **bundle of data and actions** within a class.
    1. As long as the method within the class returns the _appropriate value_ there is no need to know the inner mechanisms.
2. **Abstraction**. **Hiding** the irrelevant details.
    1. Details that are not required to be shown are _not shown_.
    2. How a method or function works is not required to be _understood_.
3. **Inheritance**. **Passing down information** between the super class and sub class.
    1. A class can inherit attributes and methods from another class.
4. **Polymorphism**. Allows for objects of a specific class to be **treated as different classes**.
    1. A class can have difference characteristics simultaneously; a square can be a rectangle and a shape, but not all rectangles are squares, and not all shapes are squares.

## Difference of Procedural and OO

In procedural:

- We think of what **functions** need to be implemented.

In OO:

- We think of what **entities** need to be implemented.