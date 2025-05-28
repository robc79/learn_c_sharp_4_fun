# Classes and objects

C# uses a style of programming called OOP (Object Oriented Programming). This
style revolves around two core things - classes and objects. In this listing we
are introduced to a simple `Greeter` class that says hello to a person.

## Listing

```csharp
void Main()
{
	var helloGreeter = new Greeter();
	helloGreeter.Greet("Steve");
}

// You can define other methods, fields, classes and namespaces here

public class Greeter
{
	public void Greet(string name)
	{
		Console.WriteLine($"Hello there, {name}!");
	}
}
```

## Explanation

## Exercises

## Next

Coming soon!
