#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Linear runtime: as n grows the the thing inside the loop grows, in a one-to-one relationship


b) Quadratic runtime: as n in the outside loop grows, the inside of the while loop group grows quadratically

c) Constant runtime: there is no growth in n in this case 

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

English:

1. I would have to create a while loop that runs while the egg doesn't break and then when an egg breaks I will have found f floor value
2. I would make it start at the ground floor and have it move along until an egg breaks

