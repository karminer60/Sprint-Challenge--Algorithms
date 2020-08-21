#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Linear runtime: it takes the inside of the loop n times to reach n cubed

b) n*log(n): the first loop is determined by the value of n while the inner while loop terminates when j is equal to 2^(log(n)) .

c) Linear runtime: runtime determined by n or bunnies- the value n determines how many times the function recurses

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

English:

1. I would have to create a while loop that runs while the egg doesn't break and then when an egg breaks I will have found f floor value
2. I would make it start at the ground floor and have it move along until an egg breaks

