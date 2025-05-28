# [1] What is programming?

Programming is the act of telling a computer what to do. This is typically done
with a set of precise instructions, typed into a text editor or IDE (Integrated
Development Environment). In the mists of time, these instructions came in a
format that was easy for the machine to understand, but hard for a human to
grasp. This made programming very awkward, and not very user friendly.

## Human languages

To solve this problem, computer science boffins invented new languages that made
it easier for a human to express what they wanted the computer to do. They also
made tools that took such human readable instructions, and turned them into
the aforementioned awkward machine instructions for the computer to run. As a
result, programming became much easier for humans, and a whole host of new
languages were born.

Much like spoken languages (English, Japanese, Esperanto...), these human
readable computer languages had similarities to each other and also differences.
Some languages were small, fast, and ran "close to the metal" of the
computer. These languages made you think about were each piece of information in
your program lived in the computer's memory, and often required several
instructions to do something simple.

Other languages were more concerned with hiding these things from the human
programmer. These languages often worked at a higher level of abstraction,
taking care of things like where in the computer's memory information lived, and
letting you do things with a smaller number of instructions. This often came at
the expense of speed.

## Machine language

In all cases, a human readable computer language must eventually be turned into
a set of instructions a computer can understand. This process is called
_compilation_, and is done with a tool called a _compiler_. The compiler takes
the human language instructions and turns them into machine instructions. The
problem here is each type of computer may speak with a different set of machine
instructions. Your Android phone, an Apple laptop, and a Windows desktop all
recognise different instruction sets.

So if you want to write a program that works on all of them, you have to compile
your human readable code several times. Each one _targetting_ a different set of
machine instructions.

## Virtual machines

But what if we could write our human readable code once, and run it on any
computer? How could that be done? Computer science boffins came to the rescue
once again with the notion of a _virtual machine_.

A virtual machine is a computer program much like your web browser or word
processor is. Unlike those programs however, the virtual machine is not designed
to be used directly by a human. Instead it takes instructions in a format often
referred to as _byte code_, and turns them into machine code on the fly.

What does this mean? It means we can write our instructions in a human readable
language, compile it to byte code instead of machine code, and run the resulting
program on any computer that has a copy of the virtual machine program.

## Introducing C# and .NET

C# is one such human readable programming language. Made by Microsoft, it leans
toward the high-level end of the spectrum. Using C# you don't have to worry so
much about where the computer stores things, or when stuff gets cleaned up. You
can often do some quite complex tasks in very few lines of code.

As long as there is a copy of .NET (pronounced Dot-Net) on the computer you want
to run the C# program, everything should run just fine. Microsoft have made sure
that .NET is available for all the major platforms - Windows, Mac, and Linux. You
can also target Android and iOS (Apple phones and iPads) with some additional
components.

C# .NET can be used to make games, websites, applications, and more. But before
you can run, you need to walk. In fact to start with it may seem like more of a
crawl! Stick with it however, and a world of fun projects is open to you.


## Next

[Setting things up](02_setting_things_up.md)