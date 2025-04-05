# Java Programming - Full Course Modules

This course serves as a comprehensive guide to learning Java programming. It contains some modules that will teach you everything from basic concepts of Java to advanced topics.

---

## Introduction to Java and Setup

### Theory

- What is Java and why it is used?
- History and evolution of Java.
- Difference between JDK, JRE, and JVM.
- Setting up Java: Installation of JDK and IDE (Eclipse, IntelliJ, NetBeans).
- Writing and running your first Java program.

### Practice

- Write a Java program to print "Hello, World!".
- Write a program to print your name.

### Questions

---

## Basic Syntax

### Theory

- Variables and Literals
- Data Types: Primitive vs. Non-primitive (Reference) Data Types.
  - Primitive Data Types includes `byte, short, int, long, float, double, boolean and char`
  - Non-primitive data types - such as `String, Arrays and Classes`, non-primitive data types are known as reference types
- Type Casting: Implicit and Explicit Casting.
  - Widening Casting (automatically) - converting a smaller type to a larger type size byte -> short -> char -> int -> long -> float -> double
  - Narrowing Casting (manually) - converting a larger type to a smaller size type double -> float -> long -> int -> char -> short -> byte
- Operators: Arithmetic, Relational, Logical, Assignment, and Bitwise Operators.
- Input and Output: Using `Scanner` for user input and `System.out.println()` for output.
- Comments: Single-line and Multi-line comments in Java.

### Practice

- Create a program that accepts two numbers as input and displays the sum of result.
- Write a program to accept the user's name and age, and print a greeting message.

### Questions

---

## Control Statements

### Theory

- Decision Making: `if`, `else`, `else-if`, `switch` statements.
- Loops: `for`, `while`, `do-while` loops.
- Loop Control: `break`, `continue`.
- Ternary Operator: `condition ? expression1 : expression2;`
  - Nested Ternary: `(n1 >= n2) ? ((n1 >=n3) ? n1 : n3) : ((n2 >= n3) ? n2 : n3);`

### Practice

- Write a program to print all numbers divisible by 3 up to 100.
- Use a `switch` statement to print the day of the week based on the number (1 for Sunday, 2 for Monday, etc.).

### Questions

---

## Arrays and Strings

### Theory

- Declaring and Initializing Arrays (1D and 2D arrays).
  - Declare an array
  - Allocate the memory of an array
  - Initialize array
  - Access elements of an array
  - Singledimensional array
  - Multidimensional array
- String class and its methods: Length of a String, Join Two Strings, Compare Two Strings, Strings are Immutable, Creating Strings Using the New Keyword, Methods of Java String
- Differences between String, StringBuilder, and StringBuffer in Java.
- Math class

### Practice

- Create a program to declare an array of integers and print the elements.
- Extract a substring from a given String.

### Questions

---

## Methods and Functions

### Theory

- Declaring Methods and Passing Parameters.
- Method Overloading: Multiple methods with the same name but different parameters.
- Scope: In Java, variables are only accessible inside the region they are created. This is called scope.
- Recursion: A method calling itself.

### Practice

- Write a method that returns the sum of two numbers.
- Implement a recursive method to calculate the factorial of a number.

### Questions

---

## Classes and Objects (OOP Basics)

### Theory

- The concept of Classes and Objects.
- Constructors: Default and Parameterized constructors.
- Static Keyword: Static Methods, Static Variables, Static Blocks, Nested Static Class
  - Java static and non-static Methods example
- The `this` keyword in Java.
  - this for Ambiguity Variable
  - this with Getters and Setters
  - this in Constructor Overloading
  - Passing this as an Argument
- The `final` keyword in Java.
  - final Variable
  - final Method
  - final Class
- Java instanceof Operator
- Access Modifiers
  - Types of Access Modifier

### Practice

- Create a class with two variables and a method to print their sum.
- Use constructors to initialize objects and print their attributes.

### Questions

---

## Object-Oriented Programming Concepts

### Theory

- Inheritance: Superclass and Subclass.
  - Types of inheritance
  - Method Overriding in Inheritance
  - super Keyword in Inheritance
  - protected Members in Inheritance
- Polymorphism: Method Overriding, Polymorphic Variables
- Abstraction: Abstract classes and Interfaces.
- Encapsulation: Using Getter and Setter methods.
- Nested and Inner Class: Non-Static Nested Class, Static Nested Class
- Java Anonymous Class
- Singleton Class
- Java enums: enum Constructor, enum Strings
- Reflection of Java Classes

### Practice

- Create a class that inherits from another class and overrides a method.
- Create an interface and implement it in a class.

### Questions

---

## Exception Handling

### Theory

- Exception hierarchy
- Exception Types
- What is an Exception, and why do exceptions occur?
- `try-catch` block for handling exceptions.
- Creating custom exceptions in Java.
- The `throw` and `throws` keywords.
- Multiple Exceptions
- Java try-with-resources
- Annotations
- Logging
- Assertions

### Practice

- Create a program that handles an `ArithmeticException` while dividing by zero.
- Create a custom exception to check for invalid input.

### Questions

---

## File Handling

### Theory

- File Handling: `canRead()`, `canWrite()`, `createNewFile()`, `delete()`, `exists()`, `getName()`, `getAbsolutePath()`, `length()`, `list()`, `mkdir()`
- Java Reader Class: `BufferedReader`, `InputStreamReader`, `FileReader`, `StringReader`
- Java Writer Class: `BufferedWriter`, `OutputStreamWriter`, `FileWriter`, `StringWriter`, `PrintWriter`

### Practice

- Create a program that writes text to a file and then reads from it.
- Write a program to check if a file exists and print its content.

### Questions

---

## Data Structures

### Theory

- Collections Framework Vs. Collection Interface
- Java Collection Interface
  - Subinterfaces of Collection
  - List Interface: `ArrayList`, `LinkedList` `Vector`, `Stack`
  - Set Interface: `HashSet`, `TreeSet`, `LinkedHashSet`, `EnumSet`, `SortedSet`, `NavigableSet`
  - Queue Interface: `ArrayDeque`, `LinkedList`, `PriorityQueue`, `Deque`, `BlockingQueue`, `BlockingDeque`
- Java Map Interface: `HashMap`, `TreeMap`, `EnumMap`, `LinkedHashMap`, `WeakHashMap`, `SortedMap`, `NavigableMap`, `ConcurrentMap`
- Java Iterator Interface
- Java Wrapper Classes

### Practice

- Create an `ArrayList`, add elements to it, and print them.
- Create a `HashSet`, add elements to it, and print them without duplicates.

### Questions

---

## Additional Topics

### Theory

- Java Threads
- Java Operator Precedence
- Java autoboxing and unboxing
- Java Lambda Expressions
- Java Regular Expressions
- Java Date and Time
- Java Packages & API
- Java Generics
  - Generics Class
  - Generics Method
  - Bounded Types
- Java Command-Line Arguments

### Practice

### Questions

## GUI (Graphical User Interface)

### Theory

- Introduction to Java Swing: `JFrame`, `JButton`, `JLabel`, `JTextField`.
- Layout Managers: `FlowLayout`, `BorderLayout`.

### Practice

- Create a `JFrame` and add a `JButton` to it.
- Use a `JTextField` to accept input from the user and display it.

### Questions

---

## Project and Real-World Applications

### Theory

- Guidelines for creating a small Java project.
- Project Ideas: Console-based Banking System, Student Management System.
- Uploading projects to GitHub for version control.

### Practice

- Create a Banking Management System.
- Create a Student Management System with features like adding, updating, and deleting student records.

### Questions

---
