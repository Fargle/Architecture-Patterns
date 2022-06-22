## Definitions

#### Responsibility-driven design
Instead of thinking about tasks, think about *roles* and *responsibilities*. This way, code becomes about behavior, rather than data and algorithms. 

#### **Layering**
When one function, module, or object uses another, we say that the one *depends on* the other. These dependencies form a graph. 

In a layered architecture, we divide our code into discrete categories or roles, and we introduce rules about which categories of code can call each other. 

*Three-layered architecture*: Presentation -> Business logic -> Database layer
* *Presentation* is in charge user-interface. 
* *Business logic* is the layer that contains specific business rules.
* *Database* is the layer that responsible for stroing and retrieving data.

#### **Dependency Inversion Principle** (DIP)
    1. High-level modules should not depend on low-level modules. Both should depend on abstractions.
    2. Abstractions should not depend on details. Instead, details should depend on abstractions.

#### **High-level modules** of a software system are the functions, classes, and packages that deal with our real-world concepts. 
#### **Low-level modules** are the things that help the high-level but in a unimportant way. 

# **Chapter 1**
## **Domain Modeling**

A **domain** is the problem you're trying to solve. 

A **model** is a map of a process or phenomenon that captures a useful property. 

## **Domain Language**
A *product* is indentified by a *SKU*, short for *stock-keeping unit*. 

An *order* is identified by an *order reference* and comprises of multiples **order lines**. 

