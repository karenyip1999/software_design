# **Software Design**

## Coupling and cohesion in structured design
`Coupling` and `cohesion` are used to measure the standard of "good" programming. 

`Coupling` measures how closely connected classes are with each other and their level of interdependence.

High coupling means changes in one class will affect other classes. Low coupling means classes are independent of one another so changes in one class wil have little impact on others.

`Cohesion` refers to a class or a method having one single well defined pupose.

High cohesion means a class or a method has one single purpose and are closely related. Low cohesion means they serve multiple purposes and are loosely related.

The goal is to have low coupling and high cohesion.

## Top- down and bottom- up design

The `top down` approach takes a big problem, or large algorithm and breaks it down into smaller methods in a process called `Modularisation`.

The `bottom up` approach takes the approach of creating methods individually and integrating them all together to create the full algorithm. 

`Structured Design` would be a top down approach.

`Function Oriented Design` is a top down approach.

`Object Oriented Design` is a bottom up approach.

## Class diagrams

`Class diagrams` are blueprints of the system as they help plan out how everything fits together. It can model classes, relationships between classes, and describes what each class can do.

Class diagrams greatly benefit Object Oriented Design.

## The 4 pillars of Object Oriented Progamming

`Abstraction -` The process of hiding unwanted information so when calling upon the method, you do not need to know exactly what it is doing.
Eg: Can drive a car without knowing how an internal combustion engine works.

`Encapsulation -` The process of removing access to parts of the system by making properties private so an object can control its own state.

`Inheritance -` The process of allowing an object to take on the properties or methods of another object.

`Polymorphism -` Allowing an object to take on many forms.
Eg: Dog extends Mammal can take on 4 legs property but can also have it's own method for making its own noise.

## Strategy pattern

Behaviours are separated from the object, allowing the object's behaviour to be changed at run time.

The implementation of this in an Object Oriented system follows the practise of programming to an interface, single responsibility of classes and open for extension but closed for modification rule.

The implementation of this in a Functional system doesn't use interfaces or different classes as higher order functions can be implemented instead.

---

#### Question: Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? 

I would choose an Object Oriented design as through inheritance, this allows for reusability of code. Through encapsulation to make properties private, these can be reused from ordering a takeaway to buying a new coat as the principles of purchasing stay the same, but the object being purchased will be different.