# maze-escape
A NetLogo Model to simulate escape from a maze

## WHAT IS IT?

A NetLog script written for version 6.1.1. A model of agent trying to find exit.  

## HOW IT WORKS

As a initial step it generates a maze according to the spacing set by the slider. It creates a network with nodes along the path. 
After agent try to find exit. At every hub it colors the path according to history. 
Green if it's the shortest path from the entrance. 
Yellow in case it still has to very if there is a blind spot at the end of the road. 
Red for those path who takes nowhere. 
In the meanwhile agent explores the world some monitors and a plot show statistics on the left side of the interface. 


## HOW TO USE IT

Press "Setup" to start
Press "Find exit" to make agent find exit 
Press "Find exit step-by-step to make agent stop after each node.

## THINGS TO NOTICE

Pay attention of how agent comes back when it finds a blind spot. 

## THINGS TO TRY

Adjust the spacing to create smaller or bigger maze.
Set debug to 1 or 2 in order to print a logger.

## EXTENDING THE MODEL

Algorithm takes into accounts that more agents could explore the maze at the same time in order to find exit faster. Future versions could support the creation of more maze runners.
A future study could create a second maze runner that take into accounts path already explored by the first maze runner. A cost function could estimate the perfect time the second maze runner needs to wait to find exit faster. 

## RELATED MODELS

This work is based on script created as a case study for a the graduation thesis: "Cooperative and optimization strategies in bio-based agents model" by C. Crespi and A. Rapisarda, A. Pluchino as supervisor. 

## CREDITS AND REFERENCES

NetLogo model developed by R. Rotondo (riccardo.rotondo@phd.unict.it) as an assignment of a PhD course.