# SOLID Design Principles

![SOLID](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20191012234920/SOLID-Principle-in-Programming-Understand-With-Real-Life-Examples.png)

## Abstract

Design is a very important phase of SDLC. It has been proven many times that designing has a significant role and has a direct impact on quality and performance. If the software design is based on some proper principles and patterns then it can increase software reusability, maintainability, and scalability. In this paper, we will be focusing on SOLID principles and see how useful they are in software design.

## Introduction

Software design helps us to imagine the overall project and has a direct impact on cost reduction in development. As we cannot identify the actual requirements at the very start of the project therefore the software should be designed in such a way that it supports scalability. To support scalability we use SOLID design principles so that we can design our software as efficiently as possible.
The term SOLID is an acronym for five design principles which was introduced by Michael Feathers.

## Development of a good application depends on -

- **Architecture** : Choosing an architecture is the first step in application design as per requirements. Example- MVC, MVVM, etc.
- **Design Principles** : The application development process needs to follow design principles.
- **Design Patterns** : We need to choose the correct design pattern to build the software.

## SOLID Acronym -

  1. **S** : Single Responsibility Principle
  2. **O** : Open closed Principle
  3. **L** : Liskov Substitution Principle
  4. **I** : Interface Segregation Principle
  5. **D** : Dependency Inversion Principle
  
## 1. Single Responsibility Principle

This principle states that **there should not be more than one reason for a class to change**. This means every class should be responsible for a single part of the functionality of the software. If a class has more than one responsibility then it can lead to fragility which means the software can break every time it is changed.

## 2. Open Close Principle

This principle states that **software entities like classes and modules should be open for extensions but closed for modifications**. This means that you should design modules that never change. When there are new requirements you extend those modules by adding new code instead of changing old code that already works.

## 3. Liskov Substitution Principle

This principle states that **objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program**. This means if a program module is using a Base class, then the reference to the Base class can be replaced with a Derived class without affecting the functionality of the program module. If there is a function that does not follow LSP then that function must know all the derivatives of that base class.

## 4. Interface Segregation Principle

This principle states that **clients should not be forced to depend upon interfaces that they do not use**. This means that we should have multiple client-specific interfaces rather than one big general-purpose interface. According to this principle, one fat interface needs to be split into many smaller interfaces so that clients can know about the interfaces that are relevant to them.

## 5. Dependency Inversion Principle

This principle states that **high level modules should not depend upon low level modules. Both should depend upon abstractions**. This means that abstractions should not depend on details whereas details should depend on abstractions. According to this principle, we should decouple high level modules from low level modules by the introduction of an abstraction layer between both high level classes and low level classes.

## Why we should follow SOLID Principles

- It helps us to reduce the complexity of the code.  
- SOLID principles make the code more readable and extendable.
- It reduces errors and improves reusability.
- With these principles, we can achieve better testability of code.
- It helps us in reducing tight coupling between modules.

## Conclusion

As the demand for software development has varied in the last few years and the focus has now shifted to the scalability of the software design.
It is important that while working on the latest tech stack, the software should scale itself as per the market competency.
Software Design should be based on Principles so that it would be easy to reuse and scale the services.

## References

- [SOLID Principles](https://www.geeksforgeeks.org/solid-principle-in-programming-understand-with-real-life-examples/)
- [Advantages of SOLID](https://csharp-video-tutorials.blogspot.com/2017/11/solid-design-principles-introduction.html)
- [Images](https://www.google.com/search?q=solid+design+principles&client=ubuntu&hs=IeO&channel=fs&sxsrf=ALiCzsaRSDXKDA_wdR4VUIAW22hDbutOsw:1652963763264&source=lnms&tbm=isch&sa=X&ved=2ahUKEwi4lL7vyev3AhW2TmwGHZTpDYQQ_AUoAnoECAEQBA&biw=1848&bih=968&dpr=1)
- [Design Principles](https://www.bmc.com/blogs/solid-design-principles/)
