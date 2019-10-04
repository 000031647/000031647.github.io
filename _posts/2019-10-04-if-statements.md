---
layout: post
title: IF Statements
categories: C# Programming
---

IF statements are used when there are multiple posibilities within the code and selection is needed.  
An IF statement should be layed out like this:
```csharp
if (//condition)
{
    //code
}
```
And this should be contained within:
```csharp
static void Main(){      }
```

Because IF statements are used for selection, there should be at least 2 different condition options.  
The very first statement should be written as shown above, and the very last one should be written like this:
```csharp
else
{
    //code
}
```

Any statements between these two should be written like this:
```csharp
else if (//condition)
{
    //code
{
```
