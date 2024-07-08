# How does it work?

There's a task to do. The idea is to discuss the design of a system that can
implement that functionality and start implementing it.

One of us should share the screen and start writing the documentation and the
code. The interviewer will have two different roles at the same time:

- Product Owner: will answer questions about the requirements and give feedback
  on the design and implementation.
- Junior developer: pairing with the other developer to implement the system.

The goal is to have an agreement about the initial design and start the
implementation. It doesn't need to be functional.

# Task

Build a microservices-based system with the following services: 

- auth
- merchant
- document
- notification
- transaction
- banking

We should implement a system with the following characteristics:

- Able to support 10_000 tps, with a 99.99% availability. Also, the system
  should be able to handle 1_000_000 tps in the future without major changes.
- Some of the services (for example, banking) should be able to provide exactly
  once semantics.
- Total freedom to choose the technologies and the architecture.

Ideally, we should be able to start the skeleton of one of the services.

# Design 


# Resources
