# Simulated Annealing
In this exercise, we will implement several local search algorithms and
test them on the Traveling Salesman Problem (TSP) between a few dozen US
state capitals.

In particular we will focus on simulated the annealing algorithm, a
version of stochastic hill climbing where some downhill moves are
allowed. Downhill moves are accepted readily early in the annealing
schedule and then less often as time goes on. The schedule input
determines the value of the temperature T as a function of time.

![Simulated Annealing](https://upload.wikimedia.org/wikipedia/commons/d/d5/Hill_Climbing_with_Simulated_Annealing.gif)