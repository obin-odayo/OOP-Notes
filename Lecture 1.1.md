## Programming Paradigm

- Fundamental _style_ of programming.
    - A style of thinking about and solving a problem.
- This is different from a programming language.
    - Paradigm:
        - Influences programming languages.
        - Serves as the philosophy of the languages.
    - Language:
        - Influenced by programming paradigms; a combination of paradigm philosophies.
- Examples:
    - Procedural Programming
    - **Object-Oriented Programming**

## Procedural Programming

- Focused is on the process.
- Instruction-driven program.
- Functions are used to generalize code repetition.
- Data can be typically accessed anywhere in the program
    - As parameters, global data, or pointers.
    - If it is not localized (e.g., declared in a function, passed as a parameter, etc.), then a function cannot call the data. In general, what stays in the function, _stays in the function._

## Object-Oriented Programming (OOP)

- Focused on objects and interaction.
- Objects can be composed of variables and perform actions; or it **has attributes** and **can perform methods**.
- Encourages **generalization** and **abstraction**.
- This paradigm grants more control over:
    - storage and access of data;
    - processes;
    - origin of the processes.
- Since OOP provides more control, it requires more effort from the programmer.
- Allows for solving large scale problems through _representation_, _behavior_, and _relationships._

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