# On Strong Stability of Explicit Runge-Kutta Methods for Nonlinear Semibounded Operators

[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3066828.svg)](https://doi.org/10.5281/zenodo.3066828)


This repository contains some code used in the article
```
@online{ranocha2018strong,
  title={On Strong Stability of Explicit {R}unge--{K}utta Methods for Nonlinear
         Semibounded Operators},
  author={Ranocha, Hendrik},
  year={2018},
  month={11},
  eprint={1811.11601},
  eprinttype={arxiv},
  eprintclass={math.NA}
}
```
> Explicit Runge-Kutta methods are classical and widespread techniques in the numerical
solution of ordinary differential equations (ODEs). Considering partial differential
equations, spatial semidiscretisations can be used to obtain systems of ODEs that are
solved subsequently, resulting in fully discrete schemes. However, certain stability
investigations of high-order methods for hyperbolic conservation laws are often conducted
only for the semidiscrete versions.
Here, strong stability (also known as monotonicity) of explicit Runge-Kutta methods
for ODEs with nonlinear and semibounded (also known as dissipative) operators is
investigated. Contrary to the linear case, it is proven that many strong stability
preserving (SSP) schemes of order two or greater are not strongly stable for general
smooth and semibounded nonlinear operators. Additionally, it is shown that there
are first order accurate explicit SSP Runge-Kutta methods that are strongly stable
(monotone) for semibounded (dissipative) and Lipschitz continuous operators.

If you find these results useful, please cite the article mentioned above. If you
use the implementations provided here, please cite this repository as
```
@misc{ranocha2018strongRepository,
  title={{StrongStabilityExplicitRungeKuttaForNonlinearOperators}. On Strong
         Stability of Explicit {R}unge--{K}utta Methods for Nonlinear Semibounded
         Operators},
  author={Ranocha, Hendrik},
  year={2018},
  month={11},
  howpublished={\url{https://github.com/ranocha/StrongStabilityExplicitRungeKuttaForNonlinearOperators}},
  doi={10.5281/zenodo.3066828}
}
```


## Disclaimer

Everything is provided as is and without warranty. Use at your own risk!
