# Game of Evolution
This program is based on Robert Alexlrod's emulation, add the element of space, coded in Python 3.6.

Robert Alexlrod has famous proposed the theory of 'the evolution of cooperation'. He used computer simulation to prove that benevolent strategy in **prisoner's dilemma** could result in mutually beneficial result in the long run. This theory could compliment the shortcoming of Darwinism, which neglected the widespread cooperation in the biosphere.

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |

Another similar approach is proposed by Richard Dawkins in chapter 5 of *The Selfish Gene*. It would be more easily simulated.



# Outline of Game

## The Game – Dawkins & ESS



## The Game – Alexlrod & Game Theory

(optimally in an OOP fashion)

* A game between two individuals, each individual has a strategy type and its own quantity of resource 
* In each term, the individual will interact with all its neighbors (four surrounding neighbors) once, and the next term it repeats. This is to simulate the continuous interaction in a group.
* Strategy explain
  * 0: 
* List of Strategy
  * tit for tat: 

* Map
    * [0] - strategy type
    * [1:5] - stored info of the last move of its four neighbors
    * [-1] - quantity of resource
  * In the beginning, each grid is randomly given a strategy type and quantity of resource.
  * In the end of each term, individual with negative resource will be replaced by the strongest neighbor. All the previous info would be cleared

# Other Resources

1. 种群结构如何影响自然选择？ | 图论对进化生物学的启发
   1. https://mp.weixin.qq.com/s/-oXSEBeVhhNmWusNWv9tCw
   2. Explore different topology of the map
2. *The Selfish Gene*  by Richard Dawkins
   1. In Chapter 5, Dawkins intorduced ESS – evolutionary stable strategy
   2. ratio of offensive individual and defensive individuals would reach an equilibrium
3. Robert Axelrod - The evolution of cooperation - revised edition (2006, Basic Books)
   1. The original book