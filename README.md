# Object Oriented Project

This project allows us to learn how to utilise Object Oriented Programming

Learning Outcomes:
- git
- github
- python OOP
- Separation of Concerns
- DRY code
- others

We will look at:
- Abstraction
- Encapsulation
- Inheritance
- Polymorphism

## Class
Classes are like cookie cutters that create instances of cookies. 

They are wrappers to define how an object looks and behaves. 
Classes will wrap characteristics as attributes and behaviors as methods

## Methods v Functions
Methods are functions that belong to a specific data type, whereas functions are anonymous, meaning that they can be given any data type.

**Methods NEED the instance to be called**

## Instance
This is a single copy or occurance of something.

### Self
This refers to the instance on which a method is being called. 

```python
self.name  = 'ringo'
```

This means that the specific object attribute will have the name ringo



### Characteristics - How an object appears
These are attributes that are assigned to each instance.
 

## Abstraction
The ability to hide complexity. You don't need to know how something works to be able to use it.

This is done by using:
- Separation of concerns
- Documentation
    - This is where you specify all the methods within a class, as well as how to use them
- Inheritance can cause abstraction too

Real life examples are everywhere.
- Changiing gears
- Heating up food in a microwave
- Entering a door with a security card

## Inheritance
The ability to pass the methods and attributes of one class to a child class.

This is one of the big reasons for OOP - it means that you can reuse code.

**Promise of reusable code**

```python
class Animal():
    pass

class Reptile(Animal):
    pass
```

## Encapsulation


## Polymorphism
Literally means MANY FORMS.

This is the ability to overwrite methods and, if need be, recall methods from parent class using super
