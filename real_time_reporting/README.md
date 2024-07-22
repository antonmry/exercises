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

In many data centers, different type of servers generate large amount of
data(events, Event in this case is status of the server in the data center) in
real-time.

There is always a need to process these data in real-time and generate insights
which will be used by the server/data center monitoring people and they have to
track these server's status regularly and find the resolution in case of issues
occurring, for better server stability.

Since the data is huge and coming in real-time, we need to choose the right
architecture with scalable storage and computation frameworks/technologies.

The system should be able to evaluate the data and generate notifications if
some conditions are met.

We should implement a system with the following characteristics:

- Able to support 10_000 request/s, with a 99.99% availability. Also, the
  system should be able to handle 1_000_000 request/s in the future without
  major changes.
- Total freedom to choose the technologies and the architecture.

Ideally, we should be able to start the skeleton of the platform.

# Design


# Resources
