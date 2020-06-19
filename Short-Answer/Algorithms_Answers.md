#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n), this question only requires one loop


b) O(n^2), this question has a nested loop as well. two loops total


c) O(log n), recursive

## Exercise II

divide n by 2 to get a possible midpoint, check if answer is to the right or left. discard either side if value is not on that side. repeat until the right floor is found. also we want to check the right side first according to the question

more likely to be O(log n), since it eliminates by half at every try
