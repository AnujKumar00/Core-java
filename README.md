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
* Type Casting
* Operators

### 3: Control Structures

* Control Structures
* Types of Control Structures
* Decision Control Structure (if, if-else, if else if, switch –case)
* Loop Control Structure (do –while, while, for)
* Jump statements (break, continue)

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

// OK, but it is not so easy to understand what m actually is
int m = 60;
```
The general rules for naming variables are:

1. Names can contain letters, digits, underscores, and dollar signs

2. Names must begin with a letter

3. Names should start with a lowercase letter, and cannot contain whitespace

4. Names can also begin with $ and _

5. Names are case-sensitive ("myVar" and "myvar" are different variables)

6. Reserved words (like Java keywords, such as int or boolean) cannot be used as names


##### Keywords

Java keywords are also known as reserved words. Keywords are particular words that act as a key to a code. These are predefined words by Java so they cannot be used as a variable or object name or class name.

##### Literals

Any constant value which can be assigned to the variable is called literal/constant. 

```
// Here 100 is a constant/literal.
int x = 100; 
```

##### Primitive Data Types, Range

A primitive data type specifies the size and type of variable values, and it has no additional methods.

There are eight primitive data types in Java:
```
Data Type   	Size    	Description
byte	        1 byte	     whole numbers from -128 to 127
short       	2 bytes	     Stores whole numbers from -32,768 to 32,767
int	        4 bytes	     Stores whole numbers from -2,147,483,648 to 2,147,483,647
long	        8 bytes	     Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807
float	        4 bytes	     Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits
double	        8 bytes      Stores fractional numbers. Sufficient for storing 15 decimal digits
boolean	        1 bit	     Stores true or false values
char	        2 bytes	     Stores a single character/letter or ASCII values
```

##### Reference (User defined) Data type

Unlike primitive data types, these are not predefined. These are user-defined data types created by programmers. These data types are used to store multiple values.

There are five types of non-primitive data types in Java. They are as follows:

1. Class
2. Object
3. String
4. Array
5. Interface

##### Type Casting

In Java, type casting is a method or process that converts a data type into another data type in both ways manually and automatically. The automatic conversion is done by the compiler and manual conversion is performed by the programmer.

##### Operators

 A symbol that is used to perform operations. For example: +, -, *, / etc.

There are many types of operators in Java which are given below:

1. Unary Operator(++, --),
2. Arithmetic Operator(+, -, *, /, %),
3. Relational Operator(<,>,etc),
4. Bitwise Operator(&, |),
5. Logical Operator(&&, ||),
6. Ternary Operator(?:) and
7. Assignment Operator(+=, -=, etc).

####  3: Control Structures

##### Control Structures

Java compiler executes the code from top to bottom. The statements in the code are executed according to the order in which they appear. However, Java provides statements that can be used to control the flow of Java code. Such statements are called control flow statements.

##### Types of Control Structures

Java provides three types of control flow statements.

1. Decision-making statements or decision-control structure
2. Loop statements
3. Jump statements

##### Decision-Control Structure

As the name suggests, decision-making statements decide which statement to execute and when

There are two types of decision-making statements in Java, i.e., the If statement and the switch statement.

##### If statement

In Java, the "if" statement is used to evaluate a condition. The control of the program is diverted depending upon the specific condition.
In Java, there are four types of if-statements given below.

1. Simple if statement
2. if-else statement
3. if-else-if ladder
4. Nested if-statement

##### 1) Simple if statement:

It is the most basic statement among all control flow statements in Java. It evaluates a Boolean expression and enables the program to enter a block of code if the expression is true.

```
if(condition) {    
statement 1; //executes when the condition is true   
}    
```

##### 2) if-else statement

The if-else statement is an extension to the if-statement, which uses another block of code, i.e., else block. The else block is executed if the condition of the if-block is evaluated as false.

```
if(condition) {    
statement 1; //executes when condition is true   
}  
else{  
statement 2; //executes when condition is false   
}
```

##### 3) if-else-if ladder:

The if-else-if statement contains the if-statement followed by multiple else-if statements. In other words, we can say that it is the chain of if-else statements that create a decision tree where the program may enter in the block of code where the condition is true. 

```
if(condition 1) {    
statement 1; //executes when condition 1 is true   
}  
else if(condition 2) {  
statement 2; //executes when condition 2 is true   
}  
else {  
statement 2; //executes when all the conditions are false   
}
```

##### 4) Nested if-statement

In nested if-statements, the if statement can contain a if or if-else statement inside another if or else-if statement.

Syntax of Nested if-statement is given below.

```
if(condition 1) {    
statement 1; //executes when condition 1 is true   
if(condition 2) {  
statement 2; //executes when condition 2 is true   
}  
else{  
statement 2; //executes when condition 2 is false   
}  
}
```
##### Switch statement

In Java, Switch statements are similar to if-else-if statements. The switch statement contains multiple blocks of code called cases and a single case is executed based on the variable which is being switched.
```
switch (expression){  
    case value1:  
     statement1;  
     break;  
    .  
    .  
    .  
    case valueN:  
     statementN;  
     break;  
    default:  
     default statement;  
}
```

##### Loop Control Structure

Loop statements are used to execute the set of instructions in a repeated order. The execution of the set of instructions depends upon a particular condition.

In Java, we have three types of loops that execute similarly. However, there are differences in their syntax and condition checking time.

* for loop
* while loop
* do-while loop

##### Java for loop

<img src="https://github.com/AnujKumar00/Core-java/blob/main/control-flow-in-java.png" width="500" height="300">

 It enables us to initialize the loop variable, check the condition, and increment/decrement in a single line of code. We use the for loop only when we exactly know the number of times, we want to execute the block of code.
 ```
for(initialization, condition, increment/decrement) {    
//block of statements    
}
```

##### while loop

<img src="" width="500" height="300">

The while loop is also used to iterate over the number of statements multiple times. However, if we don't know the number of iterations in advance, it is recommended to use a while loop. Unlike for loop, the initialization and increment/decrement doesn't take place inside the loop statement in while loop.
```
while(condition){    
//looping statements    
}
```

##### do-while loop

<img src="" width="500" height="300">

The do-while loop checks the condition at the end of the loop after executing the loop statements. When the number of iteration is not known and we have to execute the loop at least once, we can use do-while loop.

```
do     
{    
//statements    
} while (condition);
```



