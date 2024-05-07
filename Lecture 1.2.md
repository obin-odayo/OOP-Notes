
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