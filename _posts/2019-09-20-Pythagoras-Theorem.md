---
layout: post
title: Pythagoras Theorem
categories: C#
---

## Woah I did something right

```csharp
double sideA;
double sideB;
double sideC;

Console.WriteLine("Enter side length A:");
sideA = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Enter side length B:");
sideB = Convert.ToDouble(Console.ReadLine());
sideC = (sideA * sideA) + (sideB * sideB);
sideC = Math.Sqrt(sideC);
sideC = Math.Round(sideC, 2);
Console.WriteLine("The length of side C is " + sideC + "cm.");
Console.ReadLine();
```

## This program finds the hypotenuse of a right angled triangle
