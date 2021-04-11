### Local search
In this exercise, we will implement several local search algorithms and
test them on the Traveling Salesman Problem (TSP) between a few dozen US
state capitals.

The following algorithms will be investigated:
- Hill Climbing: also known as greedy local search. This algorithm only
  looks to the immediate neighbors without knowing where to go next. The
  algorithm evaluates the values of immediate neighbors and continually
  moves to the direction of the increasing value, hence the name “hill
  climbing”. The algorithm will terminate at a peak where there are no
  higher values among the neighbors.

- Local Beam Search: randomly generates k number of states and expand
  all the successors of all k states in each step. The algorithm will
  terminate when the successor has found the goal. Otherwise, it selects
  k’s best successors and iterates.

- Simulated Annealing: is inspired by the annealing process in
  metallurgy. An annealing process reshapes a hard metal or glass by
  exposing it to a high temperature and gradually cool it down until it
  maintains the new shape. Unlike the Hill Climbing algorithm, which can
  get stuck in the local maxima, Simulated Annealing is guaranteed to
  find the global maximum. The next video will explain why simulated
  annealing is a complete algorithm that is able to find the global
  maximum.
- Late Acceptance Hill Climbing: the late acceptance hill-climbing
  search algorithm combines properties of both basic hill climbing and
  simulated annealing by accepting some downhill moves when the
  neighbor's value is higher than one of the previous best values in an
  array.




![Simulated Annealing](https://upload.wikimedia.org/wikipedia/commons/d/d5/Hill_Climbing_with_Simulated_Annealing.gif)