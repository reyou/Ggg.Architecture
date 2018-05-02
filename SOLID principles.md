Markdown Syntax  
https://github.com/fletcher/MultiMarkdown/blob/master/Documentation/Markdown%20Syntax.md  

## SRP: The Single Responsibility Principle  
https://en.wikipedia.org/wiki/Single_responsibility_principle  
An active corollary to Conway’s law: The best structure for a software system is heavily 
influenced by the social structure of the organization that uses it so
that each software module has one, and only one, reason to change.
A module should be responsible to one, and only one, actor. Cohesion is the force that binds together
the code responsible to a single actor.

Cohesion: 1. the state of cohering, or of sticking together; 2. the growing together of normally distinct parts of a plant; 3. the various intermolecular forces that hold solids and liquids together.

The Single Responsibility Principle is about functions and classes—but it
reappears in a different form at two more levels. At the level of components, it
becomes the Common Closure Principle. At the architectural level, it becomes
the Axis of Change responsible for the creation of Architectural Boundaries.


## OCP: The Open-Closed Principle  
https://en.wikipedia.org/wiki/Open/closed_principle  
Bertrand Meyer made this principle famous in the 1980s. The gist is that for software 
systems to be easy to change, they must be designed to allow the behavior of those systems to be changed by adding new code, rather than
changing existing code. In other words, the behavior of a software artifact ought to be extendible,
without having to modify that artifact. A good software architecture would reduce the amount of changed code to the
barest minimum. Ideally, zero.

## LSP: The Liskov Substitution Principle  
https://en.wikipedia.org/wiki/Liskov_substitution_principle  
Barbara Liskov’s famous definition of subtypes, from 1988. In short, this
principle says that to build software systems from interchangeable parts, those
parts must adhere to a contract that allows those parts to be substituted one for
another.

## ISP: The Interface Segregation Principle  
https://en.wikipedia.org/wiki/Interface_segregation_principle  
This principle advises software designers to avoid depending on things that
they don’t use.

## DIP: The Dependency Inversion Principle  
https://en.wikipedia.org/wiki/Dependency_inversion_principle  
The code that implements high-level policy should not depend on the code that
implements low-level details. Rather, details should depend on policies.

