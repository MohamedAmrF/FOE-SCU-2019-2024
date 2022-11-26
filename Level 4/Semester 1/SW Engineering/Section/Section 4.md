# Section 4

## __Use Case Diagram:__
> Visualising tool used in UML (Unified modeling language).

- Define behaviour component of the design.
- Gives a ***High level Overview***.

### ***Stake holders*** : 
1) **Actors**: 
    - users, organizations.
    - Drawn as ***stick figures.***
    - Actors can be human or non human.
    - produce or consume data.
    - Each actor should be connected to atleast one use case.

2) **Use Cases**: (Functions/processes)
    - Describe sequence of actions.
    - Expected behaviour (**what ?** not **how ?**).
    - can be accessed by more than one actor

3) **System Boundary Box:** 
    - The box that contains the use cases.
    - Indicate scope of the system.

4) **Relationships**: 
    > ***links*** between actors and use cases.  
    1) ***Extends***:  between two use cases.
        - child use case is ***dependent*** on base case.
        - Drawn as an ***arrow*** from child use case to the base use case. (child --> base).
        - Example : bonus --> salary.
    2) ***Include***: between use cases
        - ***Mandatory***.
        - Example: withdraw --> update balance.
        - ***Dashed*** Arrow points to the child.
        - Can be ***reused***.
    3) ***Association***: between actors and use cases.  
        - Drawn as a ***line***.
    4) ***Generalization***: between two actors / can also be between two use cases.  
        - Have common traits.
        - Drawn as an close ended arrow from (admin --> employee).


Review section1: 
problem statement and srs

