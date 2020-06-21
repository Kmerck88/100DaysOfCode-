# 100Daysofcode Getting Started with C# 



 DAY 2 - Exploring integer math 

 .NET Core CLI
 * dotnet new console -n NumbersInCSharp -o .
 The int type represents an integer, a zero, positive, or negative whole number. You use the + symbol for addition. Other common mathematical operations for integers include:

- for subtraction
* for multiplication
/ for division


You've seen one of the fundamental math operations with integers. The int type represents an integer, a zero, positive, or negative whole number. You use the + symbol for addition. Other common mathematical operations for integers include:


Explore order of operations
  The C# language defines the precedence of different mathematics operations with rules consistent with the rules you learned in mathematics. Multiplication and division take precedence over addition and subtraction. 

You can force a different order of operation by adding parentheses around the operation or operations you want performed first
   d = (a + b) * c;
Console.WriteLine(d);

Explore more by combining many different operations
  d = (a + b) - 6 * c + (12 * 4) / 3 + 12;
Console.WriteLine(d);"# 100DaysOfCode-" 

Day 3 - Cont with understandinng WORKING WITH NUMBERS 

 Numerical Data Types
  Int
An int is a whole integer value, like 4, 100, or 2349. They’re a good way to count units of things. 

Double and Decimal
If we need to use a decimal value, we have a few options: float, double, and decimal. These values are useful for anything that requires more precision than a whole number, like measuring the precise location of an object in 3D space.

   Operator Shortcuts
int apple = 0;
apple = apple + 1;
Console.Write(apple); // prints 1

// a shorter way to do the same thing 
int apple = 0;
apple++;
Console.Write(apple); // prints 1
