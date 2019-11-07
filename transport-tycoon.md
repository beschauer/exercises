# Transport Tycoon Exercises for DDD



This is a set of DDD/ES exercises takes place in the universe of the [Transport Tycoon](https://en.wikipedia.org/wiki/Transport_Tycoon). It is a game "in which the player acts as an entrepreneur in control of a transport company, and can compete against rival companies to make as much profit as possible by transporting passengers and various goods by road, rail, sea and air."



![tt-1-the-game.png](/Users/rinat/proj/exercises/images/tt-1-the-game.png)



## Exercise 1

There is a map containing a Factory, Port, warehouse A and B. Factory has a small stock of containers that have to be delivered to these warehouses. There are two trucks and one ship that can carry one container at a time (trucks start at Factory, ship starts at the Port). Carrying takes a specific amount of time; transport also needs to come back.

Transport follows a simple heuristic: pick the first available container from the location, bring it to the designation, then come back home.

![tt-1-exercise.png](/Users/rinat/proj/exercises/images/tt-1-exercise.png)

Task: write a program that takes a list of cargos from the command line and prints out the number of hours that it would take to get them delivered.

| Input        | Output |
| ------------ | ------ |
| A            | 5      |
| AB           | 5      |
| BB           | 5      |
| ABB          | 7      |
| AABABBAB     | ?      |
| ABBBABAAABBB | ?      |













