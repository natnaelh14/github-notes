# C#

C# is a high-level programming language, that must go through a compilation stage before it can be understood by the computer.
It was developed by Microsoft as an object-oriented version of the C language for their .Net framework.
C# programs are not compiled to machine code.

![Alt text](/images/image.png)
![Alt text](/images/image-1.png)
![Alt text](/images/image-2.png)
![Alt text](/images/image-3.png)

```
A program that ends with .cs means it is a C# file.
```

![Alt text](/images/image-4.png)

```
The namespace is a way of organizing our code and keeping things separate.
```

![Alt text](/images/image-5.png)

```
In the top, you are stating that you are using System in this file. Instead of System.Console.WriteLine. You can just say, Console.WriteLine. Class is a container where we can store our code.
```

Main method must be a static method and it also must have a specific signature.
The Main method is the entry point of a C# application. (Libraries and services do not require a Main method as an entry point.) When the application is started, the Main method is the first method that is invoked.

![Alt text](/images/image-6.png)

```
These are called using statements.
```

![Alt text](/images/image-7.png)

```
We are declaring a variable named Random. C# includes a Random Class that we can use to generate random numbers.
```

## Console I/O

The console class provides easy ways to get input from the user and to display text. That is known as console input/output, or console I/O.
The console class provides two methods for writing to the console: WriteLine and Write.
Write is used to print data without printing the new line, while WriteLine is used to print data along with printing the new line.
When you print an object, C# uses ToString to get a string representation of the object.

Console.ReadLine() – it stores user entry as a string and you can store it in a variable. It is also used to keep the console open.

## DATATYPES

STRING, CHAR, INT, FLOAT (less precise), DOUBLE, DECIMAL (most precise), BOOL

![Alt text](/images/image-8.png)

![Alt text](/images/image-9.png)

```
You can declare a variable this way.
```

![Alt text](/images/image-10.png)

```
This is to convert string to an integer.
```

## Array

![Alt text](/images/image-11.png)

```
create array
```

![Alt text](/images/image-12.png)

```
You can also determine the length of the array, when you declare it.
```

## 2D Array

![Alt text](/images/image-13.png)

## Methods

![Alt text](/images/image-14.png)

```
Void – it is what the method returns. It means you are returning nothing.
```

![Alt text](image-15.png)
![Alt text](image-16.png)

```
The Console returns a string, so we need to convert it.
```

## Exception Handling

![Alt text](/images/image-17.png)
![Alt text](/images/image-18.png)

```
You can also specify exceptions.
```

## Classes and Objects

![Alt text](image-19.png)

```
Class is a specification (building block of an application). All the variables being declared are called class attributes.

```

![Alt text](/images/image-20.png)

```
Anatomy of a class
•	Data (represented by fields)
•	Behavior (represented by methods/function)
```

![Alt text](/images/image-21.png)

```
An object is an instance of class.
```

![Alt text](/images/image-22.png)

```
We can use “var”, the compiler know that you are of type Person.
```

## Constructor

![Alt text](/images/image-23.png)

```
Constructor is a special method inside of our class that gets called when we create an object of this class.
Constructors don’t have a return type.
If you don’t define or parameterless constructor for your class, the C# compiler created one for you. It initializes the fields of the class to their default values.
o	Number: 0
o	Boolean: false
o	Characters: empty characters
o	Any other types: null
It is best practice to use “this.title = title;”
```

![Alt text](/images/image-24.png)
![Alt text](/images/image-25.png)

```
You can’t have constructors with the same signature.
```

![Alt text](/images/image-26.png)

```
Whenever you have a class, and that class has a list of objects, you have to always initialize it.
```

![Alt text](/images/image-27.png)

```
You can use “this” keyword to share the Order initialization. Whenever the constructor is called, it will call the constructor with parameter first. You should keep this use to a minimum.

```

## Constructor Null Exception

![Alt text](/images/image-28.png)

```
If you don’t check for null, you will get “object reference not set to an instance of an object.”
```

## Params Modifier

![Alt text](/images/image-29.png)

## Ref Modifier

![Alt text](/images/image-30.png)

```
Not Recommended
```

## Out Modifier

![Alt text](/images/image-31.png)

```
Not Recommended
```

## Object Initializers

![Alt text](/images/image-32.png)

```
It is a way to quickly initializing an object without the need to call one of its constructors.
```

## Object Methods

![Alt text](/images/image-33.png)

```
Object method is a method we define inside our class that object of the class can use to either find out information or modify information.
```

![Alt text](/images/image-34.png)

## Getter and Setter

![Alt text](/images/image-35.png)

```
Private means only code inside of the class can access the variables.
```

![Alt text](/images/image-36.png)

## Static Class Attribute

![Alt text](/images/image-37.png)

```
Static Class Attributes give us information about the class not the object of the class.
```

![Alt text](/images/image-38.png)
![Alt text](image-39.png)

```
Singleton - we should only have one concept of the class in memory.
```

![Alt text](/images/image-40.png)

## Static Method and Classes

Static method is a method that belongs to the class itself.
![Alt text](/images/image-41.png)

```
You can’t create an instance of the class, when it is static.
```

![Alt text](/images/image-42.png)

## Inheritance

![Alt text](/images/image-43.png)

```
Virtual means it can be overridden on any of the subclasses.
```

![Alt text](/images/image-44.png)
![Alt text](/images/image-45.png)
