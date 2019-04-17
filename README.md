# Conjugate_Gradient_Method
## A different method from gradient descent to find minimum function 

In mathematics, the conjugate gradient method is an algorithm for the numerical solution of particular systems of linear equations, namely those whose matrix is symmetric and positive-definite. The conjugate gradient method is often implemented as an iterative algorithm, applicable to sparse systems that are too large to be handled by a direct implementation or other direct methods such as the Cholesky decomposition. Large sparse systems often arise when numerically solving partial differential equations or optimization problems.

The conjugate gradient method can also be used to solve unconstrained optimization problems such as energy minimization. It was mainly developed by Magnus Hestenes and Eduard Stiefel who programmed it on the Z4. The biconjugate gradient method provides a generalization to non-symmetric matrices. Various nonlinear conjugate gradient methods seek minima of nonlinear equations. The conjugate descent method introduced by Fletcher(1987) is one of the conjugate gradient methods. The conjugate gradient method and Quasi-Newton methods are two imporatant methods for solving nonlinear optimization problems. Since conjugate gradient method chose proper  search direction, it improves the convergence very much. The conjugate gradient method is one of the most efficient methods for solving unconstrained optimization problems.

## A comparison of the convergence

A comparison of the convergence of gradient descent with optimal step size (in green) and conjugate vector (in red) for minimizing a quadratic function associated with a given linear system. Conjugate gradient, assuming exact arithmetic, converges in at most n steps, where n is the size of the matrix of the system (here n = 2).
![Conjugate_gradient_illustration](https://user-images.githubusercontent.com/40772712/56305559-98a69080-610e-11e9-945c-24465c570d38.png)

