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

### 4. Class
A class is a code template for creating objects in Python. Objects have member variables and have behaviour associated with them.
Classes provide a means of bundling data and functionality together.

To create a class, use the keyword class:

    class [ClassName]:
    <statement-1>
    .
    .
    .
    <statement-N>
  
### 5. Object
Objects have individuality, and multiple names (in multiple scopes) can be bound to the same object. This is known as aliasing in other languages.
Objects get their variables and functions from classes.

   class MyClass:
    """A simple example class"""
    i = 12345

   def f(self):
        return 'hello world'
        
### 6. Static
Static method can neither modify object state nor class state. Static methods are restricted in what data they can access - and they’re primarily a way to namespace your methods.
 This means that a static method can be called without an object for that class.
 Python Static methods can be created in two ways. Let’s see each of the ways here:
 1. Using staticmethod()
 2. Using @staticmethod
 
### 7. Property / Attribute
In python, everything is an object. And every object has attributes and methods or functions. Attributes are described by data variables for example like name, age, height etc. Properties are special kind of attributes which have getter, setter and delete methods like get, set and delete methods.
Property lets a method to be accessed as an attribute instead of as a method with a '()'. 

### 8. Method 
Python method is a label that you can call on an object; it is a piece of code to execute on that object. But before we begin getting any deeper.In the simplest terms, a method is a function which is a member of a class. It is a label that can be called on an object and executed on that particulate object.

    class C:
    
    def my_method(self):
        print "I am a C"

    c = C()
    c.my_method()  # Prints "I am a C"

### 9. Exception
A Python program terminates as soon as it encounters an error. In Python, an error can be a syntax error or an exception. 
Exceptions are convenient in many ways for handling errors and special conditions in a program. When you think that you have a code which can produce an error then you can use exception handling.
You can raise an exception in your own program by using the raise exception statement.

Raising an exception breaks current code execution and returns the exception back until it is handled.

### 10. Unit Test

