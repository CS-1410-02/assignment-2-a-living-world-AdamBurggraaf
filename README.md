# Assignment 2: A Living World

Let's call this link a primer for the assignment to come:
  [Why do things exist? Setting the stage for evolution.](https://www.youtube.com/watch?v=oDvzbBRiNlA)
  
This assignment is meant to help you create a base which could be augmented and built on in the future. Whether it be for assignments to come, classes to come (for example AI), or even just for fun (if you think genetic algorithms are fun). 

Essentially, what you will be building here is a world with creature objects in it. This creature object will need to be built in such a way that one day it could move, sense, eat, starve, etc. But to begin with, it just needs to be created, die, and reproduce based on preset odds.'

So in terms of proper requirements, this assignment must include the following:
  1. At least three classes and/or interfaces (3 total not 3 of each). 
  2. At least two relationships.
  3. A creature class with space for creature attributes and methods (eg. chances of replicating and dying).
    Required creature-specific methods:
      1. die()
      2. reproduce()
  4. A World class with world and environment attributes and methods (eg. chances of spawning new creatures without replication).
    Required World specific methods:
      1. createCreature()
        1. This method might hit the names.txt file in this project to get a random name for your creatures.
      2. spawnFood(), etc.
  6. Support for multiple creatures within the world.
  7. Main loop where these chances are 'rolled' for a number of times in a row.

If you would like you may diverge from the Biologic theming in this assignment but please keep the broad requirements intact. For example, follow requirements 1, 2, 3, etc. but not 1.1, 1.2, 4.1.1, etc.
