# Evolutionary Computation: Weasel

A weasel walks into a bar.
The bartender asks, "What can I get you?"
Pop, goes the weasel.

![](Carnivora.png)

![](MustelidaePhylogeneticTree.jpg)

https://en.wikipedia.org/wiki/Weasel_program

http://rationalwiki.org/wiki/Dawkins_weasel


This program demonstrates evolutionary computation by evolving a string from a random set of characters into a goal string

Usage:
- Run weasel.py
- Enter the goal string (alphabetical only)
- Enter the population size (10-20 is fine) larger populations evolve faster but take more computation time
- Each generation will check its best individual against the best individual overall, if it has a higher fitness the console will output the generation number and genome of that individual
- fitness is determined by the quantity of characters matching in the genome and the goal string
