# Mathematical Programming Examples in Python

## Example 01: 
A divisor of an integer n, is an integer d so that d divides n, i.e., so that n/d ∈ ℤ. 
Write a function whose name is divisors which takes as input an integer n and returns 
the set of positive divisors of n.

## Example 02:
Using the previous problem, write an function named gcd2 which takes as input two positive integers a 
and b and returns their greatest common divisor. Instead of using Euclid's algorithm, use the previous 
part to compute the two sets of divisors of the numbers. Then intersect these sets and find the maximal element. 
Note that in Python, you can write max(S) to find the maximal element of the set S. 
(Remark: This function is much more inefficient than Euclid's algorithm!)

## Example 03:
Write a function named intersection which takes as input two sets A and B and returns 
the intersection of A and B. Do not use the intersection methods defined by Python. 
You should be able to do this with the set() function for constructing the empty set, 
one for loop for looping through elements of a set, the in statement for testing membership, 
and the add method for adding elments to a set.

## Example 04:
Write your own function named max2 which takes as input a tuple t of numbers and 
returns the maximal element of t. Do not use the max function mentioned above, 
instead loop through the elements of t to find the maximal element.

## Example 05:
Write a function set_of_squares(n) which takes as input a natural number n and returns the set
An={k^2: k ∈ ℤ and 0 ≤ k ≤ n}.

## Example 06:
For sets of numbers A and B, let A⊕B denote their sumset as defined two problems above. 
For n ∈ ℕ, let An be as in the previous problem. Use the functions defined in the two prior problems to 
compute (An ⊕ An) ⊕ (An ⊕ An) for small values of n. Let A∞ = {k^2: k ∈ ℤ}. Use the results of this calculation 
to formulate a conjecture about the nature of the set (A∞ ⊕ A∞)⊕(A∞ ⊕ A∞).
(Remark. Sets in Python are sometimes printed out of order. If you have a set X and want to see it in order, 
you can first convert it to a list with L=list(X). Then you can sort it with L.sort(). 
Then printing L printes the members of X in order. Lists will be covered soon.)

## Example 07:
Lagrange's four-square theorem states that any non-negative integer is the sum of the squares of four integers. 
Write a function lagrange_four_square(n) which takes as input a non-negative integer n and returns a quadruple (a,b,c,d) of integers 
so that n = a^2+b^2+c^2+d^2.

## Example 08:
Suppose A, B and C are subsets of ℤ. Consider the quantified statement ⋆:∀a ∈ A ∃b ∈ B such that a−b ∈ C.
Write a function called verify_star which takes as input three sets of integers A, B and C and 
returns the truth-value of ⋆ (i.e., returns True or False depending on the truth value of ⋆ in this case).

## Example 09:
Let ϵ > 0. Say that a triangle is ϵ-nearly equilateral if for any two side lengths of the triangle s1 and s2, 
the ratio s1/s2 is less than 1+ϵ. Write a function is_nearly_equilateral(P,Q,R,epsilon) which takes as input three points 
in the plane P, Q and R as well as a positive parameter epsilon and returns the truth-value of the statement 
"The triangle PQR is epsilon-nearly equilateral. (Remark: Why is unreasonable to use a function called is_equilateral(P,Q,R) 
which returns the truth-value of "The triangle PQR is equilateral?")

## Example 10:
Write a function is_square which takes as input four points in the plane with integer coordinates and returns 
the truth-value of the statement "The four points are the vertices of a square."

