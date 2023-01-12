# C# in 15 Minutes

## Comments

`//` for Single Line Comments.

`/*  comments */` for Multi Line Comments.

## Print Statement

```c#
Console.WriteLine("I am Abhinav");
```

## Variables

You can declare variables with this format => `<type> <name> = <value>;`

```c#
int i = 10;
```

`=` is used for assignment.

Strings can be declared using double quotes. => `string s = "Hello world";`

You can use float, decimal and double to represent floating-point numbers. => `double d = 42.05;`

You can use single-quotes to store characters. => `char c = 'q';`

Reference type values can be null, be aware! => `string s2 = null;`

You can store boolean values using bool type. => `bool isGood = true;`

 You can use the "var" keyword to omit the type. => `var v = 100;`
`

## Conditional Statements

### If

```c#
if(i == 10) // == means equals
{
 i = 20;
}

if(Condition){
    // Statement
}
```

### Else If

```c#
else if(i != 15) 
{
    // Statement
}
// You can use "else if" when your if condition fails. != means 'not' equals by the way.
```

### ELSE

```c#
else 
{
    //Statement
}
// And at last, the else clause when your every condition fails.

```

## Loops

### While

```c#
// This is what the while condition looks like.
while(i < 50) 
{
 i++; // C# has the "++" (Increment operator and -- for decrement operator) too.
}
```

### For

```c#
// The classic for loop. Nothing is out of the ordinary here.
for(int x = 0; x < 50; x++) 
{
 i += x; 
 // It's like "i = i + x;" but shorter. You can do "-=","*=" and "/=" too if you want to do your math like that.
}
```

## Ternary Operator

```c#
string s3 = i == 50 ? "It's 50" : "It's not 50"; 
// We have ternary operator too...
```

## Array

```c#
// Arrays
// You can create an array with a length of 10 like this. 
// Similar To JAVA
string[] sArray = new string[10]; 
sArray[0] = s; 
// Indexes starts from zero, just like it should!
sArray[1] = s2;
sArray[2] = s3;
```

## Methods

```c#
// Methods
// You can declare methods like this; 

<type> <name>(|if any|<parameter type> <parameter name>)

// You can use the "void" as the type if you don't want to return anything.

void SayHi() 
{
 Console.WriteLine("Hi"); // Print Statement
}

int Add(int x, int y)
{
 return x + y; // return keyword
}

// And you can call them like this.
SayHi();
int i2 = Add(10,20);
```

## Classes in C #

```c#
// Classes
// You can declare classes like this.
/*
 class <class name>
 {
 |if any|<property type> <property name>;
 }
*/
class Person
{
 string Name;
 string Surname;
 int Age;

 string FullName() // You can declare methods in your classes like this.
 {
 return Name + " " + Surname; // You can do string concatenation.
 }
}

// You can create an instance of your class like this;
Person p = new Person();
p.Name = "Kumar"; // You can reach the properties and methods inside your class using dot notation.
p.Surname = "Abhinav";
p.Age = 21;
string fd = p.FullName();
Console.WriteLine(fd);
```

## Happy Learning
