# .Net Full Stack Foundation Course

.Net Core
- An open source, that is cross platform running on various platforms.
- A subset of the larger .NET Framework.
- Introduced by Microsoft in 2016 and a successor to the .Net Framework.
- .Net Core is written from scratch.
- Includes APIs and frameworks such as ASP.NET


Why .NET Core ?
- Cross Platform
- Performance
- Designed to work well in cloud environments.
- Able to use lightweight editors like VSCode.
- CLI Tools
- Consistent
- Felxible deployment


<img width="619" alt="Screenshot 2024-02-15 at 10 25 34 PM" src="https://github.com/sandurpraneethapradeep/.NetFullStackFoundation_Course/assets/124273065/04834c85-afba-403c-b889-fd5d1e44efaa">


.Net CLI
- A new cross-platfrom tool
- Used for creating, restoring packages, building and publishing .Net Applications.
- Supports various commands that can be used to create, build and run .Net Core projects.
- Easily automated and integrated inot build and deployment pipelines.
- .Net CLI command structure - all commands start with driver named dotnet
- After dotnet, we can supply command (called verb) to perfrom the action.
- Each command can be followed by arguments and options.
- argument is the kind of project you wanna create.

.Net Core CLI commands

<img width="556" alt="Screenshot 2024-02-16 at 1 58 49 PM" src="https://github.com/sandurpraneethapradeep/.NetFullStackFoundation_Course/assets/124273065/6dfa3187-492d-4ab2-9598-42056fd778c3">

<img width="546" alt="Screenshot 2024-02-16 at 1 59 15 PM" src="https://github.com/sandurpraneethapradeep/.NetFullStackFoundation_Course/assets/124273065/3cae96fb-b41b-47bf-b426-710b92fbc849">


.Net Core Framework
- A set of tooling for development and deployment
- Language compiler for C# and Visual Basic is Roslyn.
- Set of framework libraries - CoreFX
- A JIT based CLR - CoreCLR
- CoreCLR is the .Net runtime used in .Net Core.



C# Programming
- OOP developed by microsoft
- runs on .Net framework
- Designed for CLI
- Huge community support
- Used to develop applications mainly modern applications
- Simple
- Type safe, type support
- Interperability
- Rich library
- Modern programming language

C# Code execution
- The source code is in C# programming language
- C# compiler checks for errors
- Then passes it to CLI or IL code
- Then JIT and CLR comes into play to converted to machine code
- In .exe or .dll files

Variables in C#
- A named storage location in computer memory
- Used to store and manipulate data in a program
- All much be declared before used
- Value stored can be changed during the program execution
- Syntax : datatype variable_name = value;

Operators in C#
- Are symbols that are used to perform operations on operands
- May be variables or constants
- Used to manipulate variables and values in a program
- Need to enter F in the postfix when declaring float.


<img width="610" alt="Screenshot 2024-02-17 at 1 28 58 PM" src="https://github.com/sandurpraneethapradeep/.NetFullStackFoundation_Course/assets/124273065/9ae0a6ae-c51c-48fe-8536-8438bc3e30ee">

Conditional statements in C#
- If
- IF else IF
- Switch case

Loop statments in C#
- For loop
- While loop
- for each loop
- Do while loo[

Jump statments in C#
- Are keywords that allows you to control the flow of the execution in a program
- Helps to terminate the loop - break
- Continue helps to skip the execution
- Goto to transfer the control to the label statment in the program
- Return terminates the execution
- Throw usued to create exceptions

Arrays in C#
- A collection of elements of same data type that are stored in contiguous memory locations.
- Each element in an array is identified by its index or position within the array, starting from 0.
- Arrays are declared using square brackets "[]" after the type name byt the array name.
- For example:

int[] arrayname = new int[5];
- arrays help in code optimization
- Random access
- easy to tranverse data
- easy to manipulate data
  
1. One dimentional array -
   Simplest type of array that contains only one row for storing data
   single set of square bracket ("[]")
   Example-
   int[] age;
   age = new int[5];
2. Mulitdimentional array -
   Needs more than one row to store data
   Also called rectangular array because it has the same length of each row.
   2-D or 3-D array or more.
   Example-
   int[,] s = new int[3,3];
3. Jagged array -
   an array of arrays
   store collection of arrays of different sizes

Strings in C#
- String is an object of System.String class that represent sequence of characters
- string is a keyword.
  Example-
  string s1 = "hello"; // creating string using string keyword
  String s2 = "welcome"; //creating string using String class
- Immutable string is creating new memory always. Not Modifiable.
- Mutable string, we are using the same memory. Modifiable

Object oriented programming in C#
- C# is an object oriented programming lanaguage.
- Has 6 features like C++

Classes and Objects in C#
- A class is a blueprint or a template for creating objects
- It defines the properties and behavious of an object
- A class can have fields, properties, methods and events.
- Syntax :
  AccessSpecifier class Name_of_class
  {
  //member variables
  //member functions
  }
- Object is a dynamically created instance of the class.
- It is created at runtime so it can be a runtime entity.

Encapsulation
- Wrapping up of data under a single unit
- Binds code together and the data it manipulates
- Protective shield that prevents code being accessed by this outside.
- Can be acheived by declaring all variables in the class as private.

Abstraction
- Only essentail details are exhibited
- Acheived using either abstract class or interface
- Abstract class - a restricted class that cannot be used to create objects(to access it, it must be inherited from another class)
- Abstract methods - can be only used in an abstract class, and it does not have a body.
  The body is provided by the derived class (inherited from)
- Acess modifiers - keywords that specify accessibility or scope of variables.
  public, private, protected, internal

Constrctors
- used to initalize an objec of a class
- has same class name
- does not have return type
- Default, copy etc

Inheritance
- Inherit fields and methods from one class to another
- new class based on existing class
- Single inheritance - derived class from base class
- Hierarchial inheritance - B inherits from A and in tuurn C inherits from A
- Multilevel inheritance
  
Ploymorphism
- Multiple forms of shape
- Parent class and child class
- Compile time polymorphism / static polymorphism - compiler identifies which method is called at compile time. Method overiding / overloading.
- Method overloading- same name in class, different number of parameters, types of parameter.
- In C# we can overload method, constructurs and indexed properties
-  Runtime polymorphism / Dynamic polymorphism
-  Method overiding - same method as defined in its base class.
-  Method overiding is used to achieve runtime polymorphism.

Abstract class
- A class that cannot be instantiated
- Serves as a base class for other classes to be inherited from.

Abstract method
- A method that does not have a body is known as an abstract method.
- The abstract keyword is used to indicate that a method is abstract.
- An abstract method is a method that is declared but not defined in a base class and its implementation is left to the deriver classes.
- An abstract method must be declared in an abstract method.

Interface
- Simlar to abstract class
- unimplemented class
- Specofoes what a class must do and not how
- Can't have private members
- By default are public and abstract
- a class can inherhit only one class at a time
- but can inherit multiple interfaces

Static class
- Cannot be instantated
- Cannot create an object of a static class
- Cannot access static members using an object
- C# static cannot contain instance constructors
- Static keyoword is used before the class keyword in a class definition to declare a static class.
- Static class members are accessed by the class name followed by the member name.
   






















