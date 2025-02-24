```csharp
using UnityEngine;
using Figma;
using GitHub;
using VisualStudio.Code;
using System;

class Program
{
    static float yearsWorking()
    {
        return 7f + 9f / 12f;
    }
    static void Main()
    {
        string[] interests = new string[]{"aerospace engineering", "aviation", "programming", "embedded development"};
        Console.WriteLine("Heyo! I'm Aaron.");
        Console.WriteLine("I've been programming for " + yearsWorking() + " years.");
        Console.WriteLine("My interests include " + String.Join(", ", interests.Skip(0).Take(interests.Length - 1)) + ", and " + interests[interests.Length-1] + ".");
    }
}
```
