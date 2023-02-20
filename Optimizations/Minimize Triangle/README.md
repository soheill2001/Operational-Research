# Minimizing Triangle

This is a Python implementation of a linear programming problem using Pyomo library. The problem consists of maximizing or minimizing an objective function subject to linear constraints.

## Problem Statement
Suppose we have a triangle with sides of length `a`, `b`, and `c`, and we know the following information:

+ The sum of the length of any two sides is always greater than the length of the third side: `a+b>c`, `a+c>b`, and `b+c>a`.
+ The length of one side is 8 units.
+ The length of another side is 7 units.
+ The length of the third side is 1 unit more than the length of the second side.

We want to find the lengths of the sides that maximize or minimize the perimeter `P=a+b+c` of the triangle.

## Solution
To solve this problem, we can use Pyomo, which is a Python-based open-source optimization modeling language that allows us to define optimization models using algebraic syntax.

## Results
Running the code will give us the maximum and minimum perimeter.