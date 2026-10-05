# Approximating-the-Dirichlet-Problem-via-Random-Walks-and-Monte-Carlo

This project solves Laplace's equation on an annulus with Dirichlet boundary conditions by simulating random walks on a grid:
-The solution at a point is the expected boundary value reached by a walk started there.
-The estimates are validated against the exact solution, and the total error is split into two: statistical error (O(M^-1/2)) and discretization error.
