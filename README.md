# CORE JAVA

<img src="https://github.com/AnujKumar00/Core-java/blob/main/20180920213806core-java.jpg" width="500" height="300">

## Table Of Content
### 1: Introduction
* What is Java?
* System Requirements
* My system configurations and software's versions 
* How to Install
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

### 4: Input Fundamentals and Array In Java

* Java program inputs
* What is Array

### 5: Object Oriented Programming

* Introduction to Object-Oriented
* Abstraction, Encapsulation, Inheritance,
* Polymorphism
* Introduction to Classes and Objects

###  06: Inheritance

* Inheritance in detail
* Sub-Classes

### 07: Access Modifiers

* Default – No keyword required
* Private
* Protected
* Public

### 08: Constructor

* Constructors
* Types of Constructor
* Constructor Rule

### 09: Reference Links

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

##### System Requirements

To use Visual Studio Code (VS Code) with the Java Development Kit (JDK), you need to ensure your system meets the requirements for both VS Code and the JDK. 
##### Visual Studio Code System Requirements for Linux

* OS: Ubuntu 14.04+, Fedora 24+, CentOS 7+

* RAM: At least 4 GB of RAM (8 GB or more recommended)

* Disk Space: 512 MB of free disk space (2 GB or more recommended)

* Processor: pentium or faster processor

##### Java Development Kit (JDK) System Requirements for Linux

* OS: Ubuntu 14.04+ or above

* RAM: At least 1 GB (4 GB or more recommended)

* Disk Space: 200 MB of free disk space for JDK installation

* Processor: Any modern Linux-compatible processor

##### My system configurations and software's versions  

  * OS: Ubuntu 24.04 LTS
   
  * RAM: 8GB
   
  * Disk Space: 256 GB
   
  * Processor: 11th Gen Intel Core i3
   
  * VS Code Version: 1.91.1
   
  * JDK Version: Java 22.0.1 


##### How to Install (In vscode)?

Vscode is an IDE. An IDE (Integrated Development Environment) is an editor used to help us write code. Though we could write
our Java code in a barebones text editor like vs code, an IDE makes our lives easier by providing handy
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

In Java, it is good practice to name classes and variables as what they are supposed to do instead of randomly naming them. Below are some naming conventions of the Java programming language. They must be followed while developing software in Java for good maintenance and readability of code. Java uses CamelCase as a practice for writing names of variables, classes and packages. 

##### Comments

Comments can be used to explain Java code and to make it more readable.

There are two types of comments in Java
1. Single-line comment
2. Multi-line comment

##### 1. Single-line comment
Single-line comments start with two forward slashes (//).

Any text after // and the end of the line is ignored by Java (will not be executed).

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

Java keywords are also known as reserved words. These are predefined words by Java so they cannot be used as a variable or object name or class name.

##### Literals

Any constant value which can be assigned to the variable is called literal/constant. 

```
// Here 100 is a constant/literal.
int x = 100; 
```

##### Primitive Data Types, Range

A primitive data type is a predefined data type.

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

There are some types of non-primitive data types in Java. They are as follows:

1. Class
2. Object
3. String
4. Array

##### Type Casting

In Java, type casting is a method or process that converts a data type into another data type. Conversion is performed by the programmer.

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

There are two types of decision-making statements in Java, i.e., the "if statement" and the "switch statement".

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
Syntax:
if(condition) {    
statement 1; //executes when the condition is true   
}    
```
```
Example:
public class Main {
    public static void main(String[] args) {
        int number = 10;

        // if statement
        if (number > 0) {
            System.out.println("The number is positive.");
        }
    }
}
```

##### Output
```
The number is positive.
```



##### 2) if-else statement

The if-else statement is an extension to the if-statement, which uses another block of code, i.e., else block. The else block is executed if the condition of the if-block is evaluated as false.

```
Syntax:
if(condition) {    
statement 1; //executes when the condition is true   
}  
else{  
statement 2; //executes when the condition is false   
}
```
```
Example:
public class Main {
    public static void main(String[] args) {
        int number = -5;

        // if-else statement
        if (number > 0) {
            System.out.println("The number is positive.");
        } else {
            System.out.println("The number is not positive.");
        }
    }
}
```
##### Output
```
The number is not positive.
```

##### 3) if-else-if ladder:

The if-else-if statement contains the if-statement followed by multiple else-if statements. In other words, we can say that it is the chain of if-else statements that creates a decision tree where the program may enter the block of code where the condition is true. 

```
Syntax:
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
```
Example:
public class Main {
    public static void main(String[] args) {
        int number = 0;

        // if-else-if ladder
        if (number > 0) {
            System.out.println("The number is positive.");
        } else if (number < 0) {
            System.out.println("The number is negative.");
        } else {
            System.out.println("The number is zero.");
        }
    }
}
```
##### Output
```
The number is Zero.
```

##### 4) Nested if-statement

In nested if-statements, the if statement can contain a if or if-else statement inside another if or else-if statement.

Syntax of Nested if-statement is given below.

```
Syntax:
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
```
Example:
public class Main {
    public static void main(String[] args) {
        int number = 10;

        // Nested if statement
        if (number > 0) {
            System.out.println("The number is positive.");

            if (number % 2 == 0) {
                System.out.println("The number is even.");
            } else {
                System.out.println("The number is odd.");
            }
        } else {
            System.out.println("The number is not positive.");
        }
    }
}
```
##### Output
```
The number is positive.
The number is even.
```

##### Switch statement

In Java, Switch statements are similar to if-else-if statements. The switch statement contains multiple blocks of code called cases and a single case is executed based on the variable which is being switched.
```
Syntax:
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
```
Example:
public class Main {
    public static void main(String[] args) {
        int day = 3;
        
        // Switch statement
        switch (day) {
            case 1:
                System.out.println("Monday");
                break;
            case 2:
                System.out.println("Tuesday");
                break;
            case 3:
                System.out.println("Wednesday");
                break;
            case 4:
                System.out.println("Thursday");
                break;
            case 5:
                System.out.println("Friday");
                break;
            case 6:
                System.out.println("Saturday");
                break;
            case 7:
                System.out.println("Sunday");
                break;
            default:
                System.out.println("Invalid day");
                break;
        }
    }
}
```
##### Output
```
Wednesday
```

##### Loop Control Structure

Loop statements are used to execute the set of instructions in a repeated order. The execution of the set of instructions depends upon a particular condition.

In Java, we have three types of loops that execute similarly. However, there are differences in their syntax and condition-checking time.

* for loop
* while loop
* do-while loop

##### Java for loop

<img src="https://github.com/AnujKumar00/Core-java/blob/main/control-flow-in-java.png" width="500" height="300">

 It enables us to initialize the loop variable, check the condition, and increment/decrement in a single line of code. We use the for loop only when we exactly know the number of times, we want to execute the block of code.
 ```
Syntax:
for(initialization, condition, increment/decrement) {    
//block of statements    
}
```
```
Example:
public class Main {
    public static void main(String[] args) {
        // For loop to print numbers from 1 to 5
        for (int i = 1; i <= 5; i++) {
            System.out.println("Number: " + i);
        }
    }
}
```
##### Output
```
Number: 1
Number: 2
Number: 3
Number: 4
Number: 5
```

##### while loop

<img src="https://github.com/AnujKumar00/Core-java/blob/main/control-flow-in-java2.png" width="500" height="300">

The while loop is also used to iterate over the number of statements multiple times. However, if we don't know the number of iterations in advance, it is recommended to use a while loop.
```
Syntax:
while(condition){    
//looping statements    
}
```
```
Example:
public class Main {
    public static void main(String[] args) {
        int i = 1; // Initialization

        // While loop to print numbers from 1 to 5
        while (i <= 5) {
            System.out.println("Number: " + i);
            i++; // Increment
        }
    }
}
```
##### Output
```
Number: 1
Number: 2
Number: 3
Number: 4
Number: 5
```

##### do-while loop

<img src="https://github.com/AnujKumar00/Core-java/blob/main/control-flow-in-java3.png" width="500" height="300">

The do-while loop checks the condition at the end of the loop after executing the loop statements. When the number of iterations is not known and we have to execute the loop at least once, we can use a do-while loop.

```
Syntax:
do     
{    
//statements    
} while (condition);
```
```
Example:
public class Main {
    public static void main(String[] args) {
        int i = 1; // Initialization

        // Do-while loop to print numbers from 1 to 5
        do {
            System.out.println("Number: " + i);
            i++; // Increment
        } while (i <= 5);
    }
}
```
##### Output
```
Number: 1
Number: 2
Number: 3
Number: 4
Number: 5

```
##### Jump statements

Jump statements are used to transfer the control of the program to the specific statements. In other words, jump statements transfer the execution control to the other part of the program. There are two types of jump statements in Java, i.e., break and continue.

Java break statement

As the name suggests, the break statement is used to break the current flow of the program and transfer the control to the next statement outside a loop. However, it breaks only the inner loop in the case of the nested loop.

Java continue statement

Unlike the break statement, the continue statement doesn't break the loop, whereas, it skips the specific part of the loop and jumps to the next iteration of the loop immediately.

#### 4: Input Fundamentals in Java

##### Java program inputs

Java Scanner class allows the user to take input from the console. It belongs to java.util package.

```
Scanner sc=new Scanner(System.in);
```
Example of integer input from user

The following example allows the user to read an integer from the System.in.
```
import java.util.*;  
class UserInputDemo   
{  
public static void main(String[] args)  
{  
Scanner sc= new Scanner(System.in);    //System.in is a standard input stream  
System.out.print("Enter first number- ");  
int a= sc.nextInt();  
System.out.print("Enter second number- ");  
int b= sc.nextInt();  
System.out.print("Enter third number- ");  
int c= sc.nextInt();  
int d=a+b+c;  
System.out.println("Total= " +d);  
}  
}  
```

##### What is Array

Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value.

To declare an array, define the variable type with square brackets:
```
int[] myNum = {10, 20, 30, 40};
```

##### Printing Array Elements:
```
for (int i = 0; i < numbers.length; i++) {
    System.out.println("Element at index " + i + ": " + numbers[i]);
}
```
##### Output
```
Element at index 0: 1
Element at index 1: 2
Element at index 2: 3
Element at index 3: 4
Element at index 4: 5
```

#### 5: Object Oriented Programming

##### Introduction to Object-Oriented

Object means a real-world entity such as a pen, chair, table, computer, watch, etc. Object-Oriented Programming is a methodology or paradigm to design a program using classes and objects. It simplifies software development and maintenance by providing some concepts:

1. Class
2. Object
3. Inheritance
4. Polymorphism
5. Abstraction
6. Encapsulation


##### Introduction to Classes and Objects

##### Classes

The collection of objects is called class.
A class can also be defined as a blueprint from which you can create an individual object.

##### Objects

Any entity that has a state and behaviour is known as an object. For example, a chair, pen, table, keyboard, bike, etc.
 
##### Abstraction, Encapsulation, Inheritance,

##### Abstraction

Hiding internal details and showing functionality is known as abstraction. For example phone call, we don't know the internal processing.

##### Encapsulation

Binding (or wrapping) code and data together into a single unit is known as encapsulation. For example, a capsule is wrapped with different medicines.

##### Inheritance

When one object acquires all the properties and behaviours of a parent object, it is known as inheritance. It provides code reusability. It is used to achieve runtime polymorphism.

##### Polymorphism

If one task is performed in different ways, it is known as polymorphism. For example: to convince the customer differently.

In Java Polymorphism is mainly divided into two types: 

1. Compile-time Polymorphism
2. Runtime Polymorphism

##### 1. Compile-time Polymorphism

Compile-time polymorphism is also known as static polymorphism and it is implemented by method overloading.

```
public class Main {
  // method to add two integers
  public int addition(int x, int y) {
    return x + y;
  }

  // method to add three integers
  public int addition(int x, int y, int z) {
    return x + y + z;
  }

  // method to add two doubles
  public double addition(double x, double y) {
    return x + y;
  }

  // Main method
  public static void main(String[] args) {
    // Creating an object of the Main method
    Main number = new Main();

    // calling the overloaded methods
    int res1 = number.addition(444, 555);
    System.out.println("Addition of two integers: " + res1);

    int res2 = number.addition(333, 444, 555);
    System.out.println("Addition of three integers: " + res2);

    double res3 = number.addition(10.15, 20.22);
    System.out.println("Addition of two doubles: " + res3);
  }
}
```
```
Addition of two integers: 999
Addition of three integers: 1332
Addition of two doubles: 30.369999999999997
```

##### 2. Runtime Polymorphism

Run time polymorphism is also known as dynamic method dispatch and it is implemented by the method overriding.
```
// Java Example: Run Time Polymorphism
class Vehicle {
  public void displayInfo() {
    System.out.println("Some vehicles are there.");
  }
}

class Car extends Vehicle {
  // Method overriding
  @Override
  public void displayInfo() {
    System.out.println("I have a Car.");
  }
}

class Bike extends Vehicle {
  // Method overriding
  @Override
  public void displayInfo() {
    System.out.println("I have a Bike.");
  }
}

public class Main {
  public static void main(String[] args) {
    Vehicle v1 = new Car(); // Upcasting
    Vehicle v2 = new Bike(); // Upcasting

    // Calling the overridden displayInfo() method of Car class
    v1.displayInfo();

    // Calling the overridden displayInfo() method of Bike class
    v2.displayInfo();
  }
}
```
```
I have a Car.
I have a Bike.
```

#### 06: Inheritance

##### What is Inheritance

Java, Inheritance is an important pillar of OOP(Object-Oriented Programming). It is the mechanism in Java by which one class is allowed to inherit the features of another class.

```
class Employee{  
 float salary=40000;  
}  
class Programmer extends Employee{  
 int bonus=10000;  
 public static void main(String args[]){  
   Programmer p=new Programmer();  
   System.out.println("Programmer salary is:"+p.salary);  
   System.out.println("Bonus of Programmer is:"+p.bonus);  
}  
}
```
```
 Programmer salary is:40000.0
 Bonus of programmer is:10000
```

##### Sub-Classes

The class that inherits from another class.
In the example below, the Car class (subclass) inherits the attributes 
```
class Vehicle {
  protected String brand = "Ford";        // Vehicle attribute
  public void honk() {                    // Vehicle method
    System.out.println("Tuut, tuut!");
  }
}

class Car extends Vehicle {
  private String modelName = "Mustang";    // Car attribute
  public static void main(String[] args) {

    // Create a myCar object
    Car myCar = new Car();

    // Call the honk() method (from the Vehicle class) on the myCar object
    myCar.honk();

    // Display the value of the brand attribute (from the Vehicle class) and the value of the modelName from the Car class
    System.out.println(myCar.brand + " " + myCar.modelName);
  }
}
```

#### 07: Access Modifiers

In Java, Access modifiers help to restrict the scope of a class, constructor, variable, method, or data member.

##### Default – No keyword required

When no access modifier is specified for a class or method, – It is said to have the default access modifier by default i.e. having default access modifiers are accessible only within the same package.

```
// Java program to illustrate default modifier 
package p1; 

// Class Geek is having Default access modifier 
class Geek 
{ 
    void display() 
    { 
        System.out.println("Hello World!"); 
    } 
} 
```
##### Private

The private access modifier is specified using the keyword private. The methods declared as private are accessible only within the class in which they are declared.
```
// Java program to illustrate error while
// Using classes from different packages with

// Private Modifier
package p1;

// Class A
class A {
    private void display()
    {
        System.out.println("Geeks");
    }
}

// Class B
class B {
    public static void main(String args[])
    {
        A obj = new A();
        // Trying to access a private method
        // of another class
        obj.display();
    }
}
```

##### Protected

The protected access modifier is specified using the keyword protected.
The methods declared as protected are accessible within the same package or subclasses in different packages.
```
// Java Program to Illustrate
// Protected Modifier
package p1;

// Class A
public class A {
    protected void display()
    {
        System.out.println("Geeks");
    }
}

```
##### Public

The public access modifier is specified using the keyword public. 
The public access modifier has the widest scope among all other access modifiers.
Classes or methods, that are declared as public are accessible from everywhere in the program. There is no restriction on the scope of public data members.

```
// Java program to illustrate 
// public modifier 
package p1; 
public class A 
{ 
public void display() 
    { 
        System.out.println("Geeks"); 
    } 
} 
```

#### 08: Constructors

##### Constructors

In Java, a Constructor is a block of codes similar to the method. It is called when an instance of the class is created. At the time of calling the constructor, memory for the object is allocated in the memory. It is a special type of method that is used to initialize the object. Every time an object is created using the new() keyword, at least one constructor is called.

##### Types of Constructors

There are two types of constructors in Java:

1. Default constructor (no-arg constructor)
2. Parameterized constructor

##### 1. Default constructor (no-arg constructor)

A constructor is called a "Default Constructor" when it doesn't have any parameters.
```
//Java Program to create and call a default constructor  
class Bike1{  
//creating a default constructor  
Bike1(){System.out.println("Bike is created");}  
//main method  
public static void main(String args[]){  
//calling a default constructor  
Bike1 b=new Bike1();  
}  
}  
```
```
Bike is created
```

##### 2. Parameterized constructor

A constructor which has a specific number of parameters is called a parameterized constructor.
```
//Java Program to demonstrate the use of the parameterized constructor.  
class Student4{  
    int id;  
    String name;  
    //creating a parameterized constructor  
    Student4(int i,String n){  
    id = i;  
    name = n;  
    }  
    //method to display the values  
    void display(){System.out.println(id+" "+name);}  
   
    public static void main(String args[]){  
    //creating objects and passing values  
    Student4 s1 = new Student4(111,"Karan");  
    Student4 s2 = new Student4(222,"Aryan");  
    //calling method to display the values of object  
    s1.display();  
    s2.display();  
   }  
}  
```
```
111 Karan
222 Aryan
```

##### Constructor's Rule

There are two rules defined for the constructor.

1. The constructor name must be the same as its class name
2. A Constructor must have no explicit return type

#### 09: Reference Links

#### 1. <a href="https://www.geeksforgeeks.org/classes-objects-java/"> `Link  >>` </a>

#### 2. <a href="https://www.javatpoint.com/inheritance-in-java"> `Link  >>`  </a>

#### 3. <a href="https://www.w3schools.com/java/java_constructors.asp"> `Link  >>`  </a>

#### 4. <a href="https://www.geeksforgeeks.org/polymorphism-in-java/"> `Link  >>`  </a>

#### 5. <a href="https://www.w3schools.com/java/java_data_types_non-prim.asp"> `Link  >>`  </a>

















