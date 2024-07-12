# CORE JAVA

<img src="https://github.com/AnujKumar00/Core-java/blob/main/20180920213806core-java.jpg" width="500" height="300">

## Table Of Content
### 1: Introduction
* What is Java?
* How to Install.
* A Simple Java Program

### 2: Fundamentals of Java Programming
* Naming convention of Java language
* Comments
* Identifiers
* Keywords
* Literals
* Primitive Data Types, Range
* Reference (User defined) Data type
* Variables (Primitive, Reference)
* Type Casting, Default Value
* Operators

### 3: Control Structures

* Control Structures
* Types of Control Structures
* Decision Control Structure (if, if-else, if else if, switch –case)
* Repetition Control Structure (do –while, while, for)

### 4: Input Fundamentals and Datatypes In Java

* Java program inputs
* Data types
* What is Array
* Instantiation of an Array

### 5: Object Oriented Programming

* Introduction to Object-Oriented
* Abstraction, Encapsulation, Inheritance,
* Polymorphism
* Introduction to Classes and Objects

###  06: Inheritance

* Complete concepts of Inheritance
* Sub-Classes
* Object Classes

### 07: Access Modifiers

* Default – No keyword required
* Private
* Protected
* Public

### 08: Constructor

* Constructors
* Types of Constructor
* Constructor Rule
* Constructor Overloading

### 09: Polymorphism

* Method overloading
* Method overriding

### 10: Reference Links

............................................................................................................................................................................................................................................................................................

#### 1: Introduction
##### What is java?

Java is a programming language and computing platform first released by Sun Microsystems in 1995
Oracle owns it, and more than 3 billion devices run Java.
It is used for:

* Mobile applications (especially Android apps)

* Desktop applications

* Web applications

* Web servers and application servers

* Games

* Database connection

##### How to Install (In vscode)?

Vscode is an IDE. An IDE (Integrated Development Environment) is an editor used to help us write code. Though we could write
our Java code in a barebones text editor like Notepad, an IDE makes our lives easier by providing handy
features like auto-correction, code suggestions, debugging tools, etc.

First, install VSCode by following the steps below:
1. Head to the Visual Studio Download page: `code.visualstudio.com/download`
2. Select the appropriate download per your Operating System.
3. If you are on a Ubuntu: your download will be a .deb file.
4. Open the terminal and navigate to the download folder by
the `cd downloads/` command.
5. Hit the `ls` command to view all files in the folder.
6. To install write `sudo dpkg -i [.deb file]` and press enter.
7. OS ask for your Ubuntu password, Enter your password and your installation is started.

Now, we are moving to install JDK by following the steps below:
1. Head to the JDK Download page: `https://www.oracle.com/java/technologies/downloads/`
2. Select the appropriate download per your Operating System.
3. If you are on a Ubuntu: your download will be a .deb file.
4. Open the terminal and navigate to the download folder by
the `cd downloads/` command.
5. Hit the `ls` command to view all files in the folder.
6. To install write `sudo dpkg -i [.deb file]` and press enter.
7. OS ask for your Ubuntu password, Enter your password and your installation is started.

Now, You are good to go!

#####  A Simple Java Program.

```
// This is a simple Java program.
// FileName: "HelloWorld.java".

class HelloWorld {
    // Your program begins with a call to main().
    // Prints "Hello, World" to the terminal window.
    public static void main(String args[])
    {
        System.out.println("Hello, World");
    }
}
```
```
Hello, World
```
#### 2: Fundamentals of Java Programming

##### Naming convention of Java language

In Java, it is good practice to name classes, variables, and methods name as what they are actually supposed to do instead of naming them randomly. Below are some naming conventions of the Java programming language. They must be followed while developing software in Java for good maintenance and readability of code. Java uses CamelCase as a practice for writing names of methods, variables, classes, packages, and constants. 

##### Comments

Comments can be used to explain Java code and to make it more readable. It can also be used to prevent execution when testing alternative code.
There are two types of comments in java
1. Single-line comment
2. Multi-line comment

##### 1. Single-line comment
Single-line comments start with two forward slashes (//).

Any text between // and the end of the line is ignored by Java (will not be executed).

This example uses a single-line comment before a line of code:
```
// This is a comment
System.out.println("Hello World");
```
##### 2. Multi-line comment
Multi-line comments start with /* and end with */.

Any text between /* and */ will be ignored by Java.

This example uses a multi-line comment (a comment block) to explain the code:
```
/* The code below will print the words Hello World
to the screen, and it is amazing */
System.out.println("Hello World");
```
#####  Identifiers

All Java variables must be identified with unique names.

These unique names are called identifiers.

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

```
// Good
int minutesPerHour = 60;

// OK, but not so easy to understand what m actually is
int m = 60;
```
The general rules for naming variables are:

Names can contain letters, digits, underscores, and dollar signs
Names must begin with a letter
Names should start with a lowercase letter, and cannot contain whitespace
Names can also begin with $ and _
Names are case-sensitive ("myVar" and "myvar" are different variables)
Reserved words (like Java keywords, such as int or boolean) cannot be used as names












