# Basics of Design patterns
</br>

  Here, We are going to talk about how you should structure classes and how these classes should collaborate. Our focus will be on building a design that reusable and extensible software that can be easily extended.
</br>

## What are Design Patterns ?

Design patterns are elegant solutions to repeating problems in software design. </br></br>
<i><b>Example:</b> May want to implement the undo mechanism in your application. That is a repeating problem in software design.</i></br></br>
Design pattern shows how you should structure your classes and how these classes should talk to each other. Mainly, there are 23 design patterns in 3 categories.


<img align="center" width="500" height="500" src="https://cdn-images-1.medium.com/max/1000/0*8nTDMelConI3FojH.jpg"/>
</br></br>

1. Creational - Different ways to create objects</br>

2. Structural  - relationships between these object </br>
3. Behavioral - interaction or communication between the object</br>

## How Design Patterns are used?</br>

<img align="center" width="500" height="500" src="https://cdn-images-1.medium.com/max/1000/1*EPASyCSLmA1APms8N3fWiQ.png"/>
</br></br>

Designers design a solution for a particular issue in the environment, and then the programmer will implement that design. The job of designer and programmer is that to reduce the gap between design and implementation. This figure basically demonstrate that how we can use patterns.</br></br>
Sometimes there is some problem occurs in our programming environment, so that particular problem is handled using design patterns.
</br></br>

### <b>Steps: </b> </br>
</br>
1. Read the pattern once through for an overview</br> 
2. Study the structure, Participants, and Collaborations sections</br>
3. Look at the sample Code section to see a concrete example of the pattern in code</br>
4. Choose names for pattern participants that are meaningful in the application context</br>
5. Define the Classes</br>
6. Define application-specific name for operations in the pattern</br>
7. Implement the operations to carry out the responsibilities and collaborations in the pattern
</br></br>

### How to select a Design Pattern?</br></br>

- Consider how design patterns solve design problems
- Scan Intent section (What is the aim of particular pattern) 
- Study how patterns interrelate
- Study Patterns of like purpose
- Examine a cause of redesign
- Consider what should be variable in our design