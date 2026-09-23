# W1 — What Weight Stabilisation Would Require

This repository contains version 2.0 of *What Weight Stabilisation
Would Require: A Finite-Window Audit of Admissibility Weights*.

Version 1 claimed to prove a common positive limit for the Q5a generator weights.
It imported a relative profile estimate never established by U1, identified
Q5a's fingerprint-response averages with shell-capacity sums without a bridge,
and assumed an unbounded fitting window. U1 version 2.0 withdraws even its former
absolute estimate. The Critical Coverage theorem bounds the stated five-block
window by depth 22 for large primes. W1's former proof of [H-w] is withdrawn;
this does not disprove [H-w].

## Result and open bridge

Theorem 4 is an exact summation inequality for a **partial-sum proxy**, conditional
on a supplied relative profile estimate and generator-to-character map.
Lemma 6 identifies a finite-depth target for a supplied profile if the same
calibrated cutoff converges to 22. Corollary 7 states the further proxy-to-response
estimate needed to infer a common limit of Q5a's actual weights. None of these
premises is supplied by O25, Q5a or U1. Q5a version 3.2 allows separate
horizontal-generator limits under [H-w′].

O25's historical 7.44 pair exponent came from O16's limited sample. O25 reports
different finite-prime fits, extending to a raw global value of 7.61 at q = 601,
and does not determine an asymptotic exponent. Those fits do not establish
summability of a limiting profile or a Born–Infeld value for a Q5a coefficient.

Version 2.0 is deposited at [Zenodo record 22925850](https://zenodo.org/record/22925850)
under the unchanged [concept DOI 10.5281/zenodo.19886319](https://doi.org/10.5281/zenodo.19886319).

## Repository contents

- Manuscript: tex/w1.tex.
- Programme references: tex/cosmochrony-bibliography.bib.
- Local build for review: out/w1.pdf.
- Publication metadata: zenodo.json, unchanged until deposit.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with
large language models, used as analytical assistants. All claims and final
formulations remain the sole responsibility of the author.
