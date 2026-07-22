===============================================================================
PROJECT: Glaisher-Kinkelin Constant Computation Engine
===============================================================================

OVERVIEW:
Calculates the Glaisher-Kinkelin constant (A ≈ 1.28242712910062263687...) to 
arbitrary precision (N digits). A plays a major role in asymptotic expansions of 
hyperfactorials, the Barnes G-function, and quantum field theory partition functions.

ALGORITHM & MATHEMATICS:
- Formula:
    A = exp(1/12 - zeta'(-1))
- Evaluates derivative of Riemann Zeta function using high-precision mpmath + gmpy2.
