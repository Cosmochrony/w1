# W1 — Weight Stabilisation of the Admissible Dirichlet Form

This repository contains the source of the **W1 Cosmochrony paper**
*Weight Stabilisation of the Admissible Dirichlet Form: Proof of Hypothesis [H-w] from
Spectral Universality*.

This paper closes open problem Q5a-O3 by proving Hypothesis [H-w].

## Core Result

The admissibility weights $a_q(s)$ that enter the filtered Dirichlet form $\mathcal{E}_q$
**converge to a positive constant $A > 0$ uniformly** in the generator $s \in S_q$. The proof
has two logically distinct steps:

1. The uniform spectral universality theorem U1 gives
   $|a_q(s) - A_q| \le C q^{-1/2} A_q$, where $A_q = \sum_{n=1}^{n_*}\sigma_*(n)$ is the partial
   sum of the limit profile;
2. A separate lemma shows $A_q \nearrow A > 0$: the series $\sum_n \sigma_*(n)$ converges (by the
   O-series condition $\delta^*/2 > 1$, empirically $\delta_{\mathrm{pair}} \approx 9.5$–$10$) and
   is bounded below by the non-trivial first term $\sigma_*(1) > 0$.

$A$ is identified as a functional of $c_{\mathrm{BI}}$ and the Heisenberg BFS growth data
(addressing Q5a-O5 at the structural level). After this paper, the proof of Q5a Theorem T3
(Mosco convergence) requires only [H1], [H-E1], and [C].

## Keywords

Admissibility weights, Dirichlet form, spectral universality, Mosco convergence,
Born–Infeld bound, Heisenberg BFS growth.

## Repository Contents

```
w1/
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib)
├── out/         # Compiled paper PDF (w1.pdf)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 📄 [Paper PDF](out/w1.pdf)
- 🔗 DOI: [10.5281/zenodo.19886319](https://doi.org/10.5281/zenodo.19886319)
- 🌐 Website: https://cosmochrony.org/science/emergent-geometry/w1/

## Citation

> J. Beau, *Weight Stabilisation of the Admissible Dirichlet Form: Proof of Hypothesis [H-w]
> from Spectral Universality*, Zenodo, 2026. DOI: 10.5281/zenodo.19886319.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large
language models, used as analytical assistants. All claims and final formulations remain
the sole responsibility of the author.
