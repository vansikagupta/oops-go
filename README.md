## What is Object Oriented Programming
Structuring application and programs such that they revolve around certain entities with attributes and behaviours, and how they interact with each other. 
It is a paradigm of programming that makes your code base organized in a OO way.

## Does Go support OOP?
- OOP has certain principles and patterns. Go is not strictly OO but it supports lightweight OO principles.
- We can leverage the object oriented principles to write more structured and understandable code with Go.

## OO Principles and Patterns
- 4 pillars or basics concepts of OOP - Encapsulation, Abstraction, Inheritance and Polymorphism

### Encapsulation 
As we are dealing with entities in OOP, the entity has certain attributes and behaviors,
- Binding functions/behaviour and types/attributes together (the purpose becomes clearer and thoughtless usage can be prevented) and 
- Protecting private data (preventing direct access to values).

### Abstraction
- Having an easy-to-use interface that hides away the implementation details.
- Helps abstract the implemention chnages from the consumer of the behavior.

### Inheritance
- Helps organize entities hierarchically. Establishes IS-A relationship, Generalisation to Specialisation.
- Child class inherits the properties of the parent class. Common properties are shared, special properties are modified or extended.
- Ant(child class){specialisation} IS-A Insect(parent class){generalisation}. All Insects have 6 limbs. Ant is small, Grasshoper is bigger.

### Polymorphism
A property of having many forms.


continue https://www.toptal.com/go/golang-oop-tutorial

(Encapsulation, Composition, Polymorphism and Inheritance)

1. Binding methods to a type.
2. Composition through embedding. 
3. Use of Constructor on a type.
4. Polymorphism - property of having many/multiple forms.
    - Polymorphism in Go the right way - Interfaces.
5. No Inheritance (HAS-A instead of IS-A; Composition over inheritance)
6. Dependency Injection - No constructor should call another constructor.

## OO Analysis and Design
- Identify the entities/objects in the system.
- Understand how objects interact with one another.
- UML helps visualizing and documenting the system. (UML is not specific to object oriented programming)
- Use Case Diagram helps visualize the functional 
-and Activity Diagram might be useful

## Conventions
- Class : Struct with methods
- Constructor : NewT(params) or New(params)

## References
- OOP pillars - https://www.indeed.com/career-advice/career-development/what-is-object-oriented-programming