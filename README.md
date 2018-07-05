# Game of Evolution
Based on Robert Alexlrod's emulation, add the element of space, coded in Python 3.6.

Here is a small outline of the program's structure:

* The Game
  * A game between two individuals, each individual has a strategy type and its own quantity of resource 
  * In each term, the individual will interact with all its neighbors (four surrounding neighbors) once, and the next term it repeats. This is to simulate the continuous interaction in a group.
* Map
    * [0] - strategy type
    * [1:5] - stored info with four of its neighbors
    * [-1] - quantity of resource
  * In the beginning, each grid is randomly given a strategy type and quantity of resource.
  * In the end of each term, individual with negative resource will be replaced by the strongest neighbor. All the previous info would be cleared