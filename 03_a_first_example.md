# [3] A first example

Here we are introduced to a first C# program that says hello to the world.

## Listing

```csharp
void Main()
{
	Console.WriteLine("Hello, world!");
}

// You can define other methods, fields, classes and namespaces here
```

## Explanation

This is the traditional first program in pretty much any programming language.
Once you have typed it in, click the big green arrow above the editor pane to
run your program. You should see a new pane appear below the editor pane, with
the message `Hello, World!` in it.

Errors? Check your code against the listing. Make sure all the capitalisation
and punctuation is correct.

Lets break down each line of the program.

```csharp
void Main()
```

This is a special line. When we run our program, the computer needs to know
where in our program file to start running from. This line is that place - the
program will start here and run whatever follows.

Technically what this line does is define a method called `Main`. A method is a
named piece of your program. We'll talk more about methods in the exercises that
follow. The empty parentheses `()` tell the computer that the `Main` method has
no _parameters_. Parameters are optional values that can be given to your method
to do something with. The word `void` means the method `Main` doesn't give a
value back when it finishes.

Don't worry if that doesn't make complete sense yet, we will explore methods in
more depth very soon.

```csharp
{
```

This opening brace defines the start of the `Main` method.

```csharp
	Console.WriteLine("Hello, world!");
```

This line is part of the `Main` method because it appears between the opening
brace `{` and closing brace `}` characters on the lines above and below. It is
also indented by a tab character to increase readability.  It uses something
called `Console` (a _class_) to invoke another method `WriteLine`. This method
has some text between its parentheses enclosed in double quote `"` marks. This
text - `"Hello, world!"` is considered to be an _argument_ passed to the
`WriteLine` method.

```csharp
}
```

This closing brace defines the end of the `Main` method.

```csharp
// You can define other methods, fields, classes and namespaces here
```

This final line is a _comment_. Comments are for the benefit of human readers
and are ignored by the computer. In C# comments start with a a double forward
slash `//` and run until the end of the line. This comment is added in
automatically by LinqPad, and is telling us where we can write additional
program code. It can safely be forgotten about for now.

All of this will be explored in more depth very soon. For now it is enough to 
know that program code is organised into methods. The `Main` method is special,
as it is were the computer starts running our program from. Methods can
optionally take arguments - pieces of information to do something with - and
optionally return values. Methods live on things called classes, which for now
can be thought of as yet more names for organising your program code.

## Exercises

1. What is special about the line `void Main()`?

2. Remove the semi-colon `;` character from the end of the `Console.WriteLine`
line and re-run the program. What happens?

3. Add the semi-colon back in. Remove the last brace `}` character from the
code and re-run the program. What happens now? Is the error the same or
different?

4. Change the message used by the `WriteLine` method to say `Goodbye, world!`.
Re-run your program. What is output in the results pane?

5. Add the brace back in. Write a new line of code under the existing
`Console.WriteLine` but before the closing brace `}`. This line of code should
print out the message `Ready?, Let's go!` when the program is re-run.

## Next

[Classes and objects](04_classes_and_objects.md)