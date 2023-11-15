# Inheritance

## Aim:
To write a C# program to print some messages using hierarchical inheritance

## Algorithm:

### Step 1:
Create a base class.
### Step 2:
Create two child class.
### Step 3:
Create a constructor in the base class and print a message.
### Step 4:
create a function in child class to print a message.

## Program:
```
using System;

class tyre
{
    public virtual void Display()
    {
        Console.WriteLine("This is base class : Dhanush");
    }
}
class scooter : tyre
{
    public override void Display()
    {
        base.Display();
        Console.WriteLine("This is the first derived class of base class: Praboo");
    }
}
class car : tyre
{
    public override void Display()
    {
        base.Display();
        Console.WriteLine("This is the second derived class of base class : S");
    }
}
class program
{
    static void Main()
    {
        scooter s = new scooter();
        s.Display();
        car c = new car();
        c.Display();
    }
}
```

## Output:
![1](https://github.com/Naveenvetrivel/Inheritance/assets/94165322/8a5f0f6a-a8fe-44ef-b87a-e0196cf2b6cd)


## Result
C# program to print some messages using hierarchical inheritance is implemented successfully.
