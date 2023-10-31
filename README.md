# softwaredesign_lab

1.
Coupling - the degree of interdependence between software modules. High coupling means modules are closely connected, so changes in one module likely affect other modules. Low coupling means modules are independent and changes in one module have little impact on other modules.

Cohesion - the degree to which elements in a given module work together to fulfill a single clearly defined purpose. High cohesion means elements are closely related and focused on the single purpose, while low cohesion means that elements are loosely related and serve multiple purposes.

Coupling and cohesion are both important factors in determining the maintainability, scalability, and reliability of a software system. High coupling and low cohesion can make a system difficult to change and test, while low coupling and high cohesion make a system easier to maintain and improve.

2.
The top-down approach involves designing the overall architecture of what we're building first and then breaking it down into smaller components.

The bottom-up approach starts with smaller, self-contained components and gradually combines them to form a larger system.

Bottom up best emphasises a function oriented design, as functions are built and tested first and then combined.

3.
Object Oriented Design. The focus is on modelling systems using classes and objects to represent various behaviour or data, which class diagrams help to represent.

4.
Encapsulation - the principle of bundling data and methods into a single class and controlling access to the data to ensure privacy.

Abstraction - simplifying of complex systems by creating classes that represent the essential properties and behaviors while hiding the unnecessary details.

Inheritance - allows a new class to inherit attributes and behaviors from an existing class, promoting code reuse and establishing a hierarchical relationship between classes.

Polymorphism - enables objects of different classes to be treated as objects of a common superclass, allowing for flexibility and extensibility in code through method overriding and interfaces.

5.
The Strategy Pattern is a design pattern that allows you to define a family of interchangeable algorithms. In an object-oriented system, it's implemented using classes and interfaces, with strategies as objects. In a functional system, it's implemented using higher-order functions, treating strategies as functions. The core concept remains the same, but the implementation details vary.

6. Object Oriented Design. As I mentioned in Q3, the focus is on modellung systems to represent various behaviors, it is not function or structure specific. OOD supports inheritnace, which is great for applying certian behaviours (a generlaied payment method) to various different sub classes (specialised payment methods).

