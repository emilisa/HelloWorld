HelloWorld
==========

Commitment

using System;

class ColorizedHelloWorld

{

    static void Main()
    
    {
        Hello();
        World();
        Console.Write("\n");
        Console.ReadKey();
    }

    static void Hello()
    {
        Console.ForegroundColor = ConsoleColor.Green;
        Console.Write("Hello");
        Console.ResetColor();
    }

    static void World()
    {
        Console.ForegroundColor = ConsoleColor.Yellow;
        Console.Write(" World");
        Console.ResetColor();
    }
}
