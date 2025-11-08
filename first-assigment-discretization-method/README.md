# Consider the Cauchy problem:

u_t = u,

with u(0) = u0 ,

the same reported in the Notes. 

1) Write a python code that discretize the solution u = u0 exp(t) in three different ways:

- Explicit Euler formula

- Implicit Euler formula

- Trapezium formula

and plot these three solutions together with the analytical one.

2) Plot also the error (absolute and relative) with respect to the analytical solution for each method.

Some tips:

- build a temporal array where the time step is your temporal interval "k"

- you can define specific function to evaluate separately the different solutions

- you find the iterative formulas in the Notes ("Discretization" section)
