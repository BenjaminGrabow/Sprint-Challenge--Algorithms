#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
Time Complexity: O(n)
because: (10 * 10 * 10) / (10 * 10) = 10
every iteration a gets added with n * n until a is equal or bigger than n * n * n

b)
Time Complexity: O(n log n)
because we have a for loop with O(n)
and a nested while loop whichs loops until the var j (which is 1)
got multiplied by 2 every iteration until it reaches the value of n or get higher than n 


c)
Time Complexity: O(n)
This a recursive function.
When we call bunnyEars(5)
the function returs bunnyEars(4)
then bunnyEars(3)
then bunnyEars(2)
then bunnyEars(1)
then bunyEars(0) and we trigger the base case :
if bunnies == 0: return 0

## Exercise II

A naive solution would be to use a iterative solution with a Time complexity of (Worst case: O big Notation) O(n) where we loop
through the n array and drop every time the eye until we find the first floor where the egg gets broken => calculate current index minus one and we found f.


A way more efficient way would be to use binary search.
We go every iteration to the middle of the n array and drop the egg.
If the egg dont got broken we delete the left side and continue (again go to middle of n array and check if eye gets broken or not) until the eye gets broken and then we delete the right side because we know our target(f) is in the left side => continue until target (f) is found.

Big O Notation(worst case) O(log(n))



