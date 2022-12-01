# Homework: Farmer's problem

The Farmer's problem, also known as the [Wolf, goat, and cabbage](https://en.wikipedia.org/wiki/Wolf,_goat_and_cabbage_problem) problem, is the following problem (description from Wikipedia:

> A farmer went to a market and purchased a wolf, a goat, and a cabbage. On his way home, the farmer came to the bank of a river and rented a boat. But crossing the river by boat, the farmer could carry only himself and a single one of his purchases: the wolf, the goat, or the cabbage. If left unattended together, the wolf would eat the goat, or the goat would eat the cabbage. The farmer's challenge was to carry himself and his purchases to the far bank of the river, leaving each purchase intact.

Solve the problem (find an optimal plan) using the `planner` module. Output the number boat rides needed, and some reasonable description of the direction and boat occupants for each ride. (Only the farmer can row the boat.) Running
```
picat farmer.pi
```
should output the value `7` and some description of the seven boat rides required. Optionally, you can create a constraint model and use the cp solver.