## Overview of Java

An **object-oriented** language.

- **Object-oriented** implies the support of most concepts that make up an OO environment.
- **Object-based** implies support of object creation but lacks support for higher OO concepts.

A compiled and interpreted language.

## Compiled Language

1. We first have a high level programing language **source code**.
2. A software program, **the compiler**, translates the high level language program into an executable machine language program.
3. The **executable file** will be created that can be executed many times but on one type of computer only.

Source Code -> Compiler -> Executable File

## Interpreted Language

1. We first have a high level programming language **source code**.
2. With an **interpreter**, the source code is translated and executed one instruction at a time.

## Java as Compiled and Interpreted

1. First we have the Java **source code.**
2. Then, it is **compiled** using the `javac` command. This command translate the source code to a Java **bytecode** (the machine language of the virtual machine).
3. Finally, the Java bytecode is interpreted using the `java` command.
4. This interpreted program can be ran on any device as long as it has Java.

code.java -> code.class -> `Java Virtual Machine` -> run code

## Writing Java Application

A Java application consists of one or more Java classes.

- The file extension is `.java`
- The file name must be the class name (case sensitive).

     public class code {

     }

So for the code snippet above, the file name is `code.java` since the class name is `code`.