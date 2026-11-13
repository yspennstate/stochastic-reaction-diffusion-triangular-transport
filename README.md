# Global solutions of stochastic reaction-diffusion systems with triangular structure and species-dependent transport noise

Yitzchak Shmalo

The paper (`main.tex`, `main.pdf`) treats Problem 7 of A. Agresti and M. Veraar, *Nonlinear SPDEs and maximal regularity: an extended survey*, NoDEA 32 (2025), article 123 (arXiv:2501.18561): global well-posedness of the reaction-diffusion system (8.14) of the survey with transport noise, when the reactions are quasi-positive, of polynomial growth, satisfy mass control and a triangular condition.

The system is

    du_i = (nu_i Delta u_i + f_i(u)) dt + sum_n ((b_{n,i} . grad) u_i + g_{n,i}(u)) dW^n,   i = 1, ..., l,

on the torus T^d, d >= 2, with Hölder transport coefficients (b_{n,i})_n in C^gamma(T^d; l^2), allowed to differ from species to species under uniform stochastic parabolicity, and globally Lipschitz zero-order noise g_i vanishing on the face u_i = 0. For every nonnegative initial datum in the local-theory class, the maximal local strong solution is global almost surely. It is nonnegative and pathwise unique in its local solution class, and it is Hölder continuous in time and space on (0, infinity).

The proof uses a mixed polynomial energy adapted to the triangular structure, following the deterministic method of Fitzgibbon, Morgan, Tang and Yin. The stochastic part is a covariance estimate for this energy under species-dependent transport. It holds for the polynomial constructed here, and the paper shows that it fails for an arbitrary mixed Hessian. A stopped energy estimate, positivity and the blow-up criterion of the survey then give nonexplosion.

The result is stated on the torus with Lipschitz zero-order noise. The whole space, bounded domains with boundary conditions, and superlinear zero-order noise remain open. No continuous-dependence statement is made.

The paper is part of the Math Brain project: https://github.com/yspennstate/math-brain-public

## Files

- `main.tex`: LaTeX source (amsart)
- `main.pdf`: compiled paper, 13 pages
