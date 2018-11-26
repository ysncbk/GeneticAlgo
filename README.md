# GeneticAlgo
Genetic Algorithms- Mutations/Mutations+Selection

Task 1
(Mutations only – Ignore the Parent
Consider the same set S = {0,1}^100 as before – we call it state space, now.
Write a Python code that starts with an initial all-zero state x ini = (0,0, ... ). This is your initial
individual.
In a loop, create 200 further generations. In order to create a new generation, take the current individual,
and randomly flip one of its bits.
Repeat the whole experiment 1000 times and plot all the values, that is, the sum of the 100 components,
versus the respective generation number in order to show how values evolve over time.
In a second plot, show the average progress made by the ensemble, that is, the difference between the
new and the old mean value per generation – again versus the generation number.

Task 2
Mutations + Selection (Children plus Parent)
In the same way as above, study a slightly different scenario where a parent creates c children – each
based on a single bit flip, and the new individual is best(children, parent). Create plots as in task 1 for c =
1, c=3, and c = 5. Also plot our theory curves for the expected improvement per generation
E[improvement] = 1 − ( K/N)^c and compare.

Task 3
Larger Mutations + Selection (Children plus Parent)
Repeat task 2 but consider f bit flips rather than a single one. Summarize the consequences of such an
enhanced mutation.
