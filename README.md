[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

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

## Usage

```bash
python "Glaisher-Kinkelin Constant.py" --help
```
