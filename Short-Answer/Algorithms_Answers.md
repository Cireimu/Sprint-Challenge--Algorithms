#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n), because there's one while loop that includes a linear operation (at least I believe it's called a linear) in the form of "n\*n" on line 11 it will the runtime will scale with the value of n, as it gets bigger the run time will only get longer and longer

b) O(n log(n)), since the top for loop time complexity scales with the linear value of n for a time complexity of O(n), but when taking into account the while loop that's nested within the for loop it becomes O(n log(n)), this is due to the index doubling with each loop iteration which is a time complexity of O(log(n)).

c) O(n), I think this since it's recursion and bunnies(the n of this example) increases the number of recursive loops that but it runs at a constant

## Exercise II

To solve this issue I would first find the middle "floor" of the "building" and drop the egg, if the egg breaks from this height we can determine that the value of f is the current floor or below and as a result we can completely ignore any floor above us. In the case that the egg doesn't break upon being dropped, we know that the floor that will cause the egg to break if we drop it is above the current floor from which it was just dropped.

We continue finding the middle floor and dropping from there and overall continuing the same process as described previously until we find the absolute lowest flower from which the egg will break upon being dropped.

The time complexity of this solution would be about O(log n)
