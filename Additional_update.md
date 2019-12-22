# Getting Started with Python

### 1. How Python uses Indentation to control Flow
“Control flow” in your code is to affect the order in which the code in your program is executed.
Up until this point in the course, you have seen code that executes linearly; for example:

simple code without any "control flow" and code encapsulation

x = 6

y = 23

print("x + y = ", x + y)

print("x - y = ", x - y)

### 2. Don't Repeat Yourself
The term "don't repeat yourself" was coined in 1999 by Andy Hunt and Dave Thomas in their book The Pragmatic Programmer. They defined it as "Every piece of knowledge must have a single, unambiguous, authoritative representation within a system." In software engineering, DRY is the principle of reducing repetition in the code.
 When applied successfully, any modification or change of any single element of a system does not require a change in other logically unrelated elements. Additionally, elements that are logically related all change uniformly and kept in sync.
 
### 3.Design Patterns from Gang of Four 
he Gang of Four are the four authors of the book, "Design Patterns: Elements of Reusable Object-Oriented Software". In this article their twenty-three design patterns are described with links to UML diagrams, source code and real-world examples for each.
This section gives a high-level description of the twenty-three design patterns described by the Gang of Four. Each pattern description includes a link to a more detailed article describing the design pattern and including a UML diagram, template source code and a real-world example programmed using C#.

*Creational Patterns*
- Abstract Factory. 
- Builder
- Factory Method
- Prototype
- Singleton

*Structural Patterns*
- Adapter
- Bridge
- Composite
- Decorator
- Facade
- Flyweight
- Proxy

*Behavioural Patterns*
- Chain of Responsibility
- Command
- Interpreter
- Iterator
- Memento
- Mediator
- state
- Observer
- Strategy
- Visitor
- Template Method

###4. Class
A class is a code template for creating objects in Python. Objects have member variables and have behaviour associated with them.
Classes provide a means of bundling data and functionality together.

To create a class, use the keyword class:

    class [ClassName]:
    <statement-1>
    .
    .
    .
    <statement-N>


