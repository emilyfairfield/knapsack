# knapsack
The knapsack problem is a classic problem in which a person has a knapsack with limited capacity, which they seek to fill with the combination of objects resulting in the highest total value.

I've formulated this problem as an integer linear program, which is one where all decision variables must have integer values (you can't pack half of an object in the knapsack).

I use the scipy.optimize library.