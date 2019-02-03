# otl
# Road intersection graph

Jasmín Alejandra Marín Pérez (201910019991)

# Description of program:

The program represents the possible intersections of the streets. Understanding each point or vertex as the streets and edges or joints, as the possible relationships between the streets. The program accepts as input the compatible turns and divides this set in the least number of solutions, without there being collisions in each group. For this, a strategy called Node family was used. 

For example, in the case of edge AB -- AC, AB is understood as the vertex father and AC as the vertex son. 

Each parent vertex can have zero or several children and a child can has or has not a father.

Initially all vertex or points are related and at the end those indicate the cycles and vertices that can cross without causing collision.

The program adapts to N vertex and edges, and its result is optimal because it determines the least number of cycles or compatible turns.

# Information on how to compile and use the program:

The compilation was performed with the following steps:
•	The Declaration of objects, attributes and variables to be used
•	Data cleanup
•	Conditions for each relationship
•	Generation of final lists
•	To print

#Operating system version used:
Windows 10.

# Programming language and compiler version used:
The programming language is Python 3.0, with the libraries of Graphviz.

