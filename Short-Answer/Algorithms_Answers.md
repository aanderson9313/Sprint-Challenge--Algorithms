#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 0(n)
number of loops depends on n - runs relative to value of n
a grows with n


b) 0(n log n)
first part is 0(n) because the rate is the same
second part doubles which makes it 0(n log n)

c) 0(n)
recursive but based on elements

## Exercise II

I would start with a binary search in the middle floor
if the egg breaks, move to the middle of the bottom and middle floor
if it doesn't break, I would go to the middle between the top and middle floors.
this would be 0(log n) because we reduce the number of guesses with each loop, and canceling out half of the options leaves us with the least amount of broken eggs