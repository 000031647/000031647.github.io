---
layout: post
title: Switch Case
categories: C# Programming
---

Switch case is another form of selection (see IF statements), and allows the user to enter an option (usually a number or letter) to have a task carried out.  
Here is a practical example of the use of a switch case:
```csharp
string vLetter;

Console.WriteLine("Please a letter A-E:");
vLetter = Console.ReadLine();
vLetter = vLetter.ToUpper();
switch (vLetter)
{
    case "A":
        Console.WriteLine("You selected A\nAPPLE");
        break;
    case "B":
        Console.WriteLine("You selected B\nBANANA");
        break;
    case "C":
        Console.WriteLine("You selected C\nCOCONUT");
        break;
    case "D":
        Console.WriteLine("You selected D\nDRAGONFRUIT");
        break;
    case "E":
        Console.WriteLine("You selected E\nELDERBERRY");
        break;
    default:
        Console.WriteLine("The letter you entered was not between A and E");
        break;
}
Console.ReadLine();
```
This program allows the user to enter a letter between A and E, and then names a fruit that begins with that letter.
