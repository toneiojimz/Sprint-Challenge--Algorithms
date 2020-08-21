#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.


## Exercise I

a) O(n) will loop based on n


b) O(n^2) outer loop and inner loop


c) O(n) because of recursion

## Exercise II

n = number of floors
f-1 = floor at which an egg is safe

Binary search comes to mind, dividing n by 2 to find a midpoint. 

check if f-1 is on the left or right side of my midpoint. 
repeat until f-1 is found. 
by splitting in half every time, we minimize the number of times we have to check for the floor at which an egg is safe

time complexity should be O(log n)