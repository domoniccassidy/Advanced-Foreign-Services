# 5. Architectural Style Decision

## Context and Problem Statement

What architectural style will meet the most high priority non-functional requirements.

## Considered Options

* Event Driven
* Service Oriented
* Layered

## Decision Outcome

Chosen option is Service Oriented because it is easier to maintain due to the services being separate. Also improved flexibility and scalability as individual services can be scaled up and down as required. There is also increased availability as the system can be repaired quicker 

The only observed negative of this style is the potential poor performance due to extra requests increasing bandwidth.

### Consquences
We meet the most important non-functional requirements by implementing this architectural style and so this will drive the project to succeed.

## Confirmation
Accepted on 2023-10-24
