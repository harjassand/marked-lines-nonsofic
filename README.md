# A Torsion-Free Nonsofic Hyperbolic Group from Marked Lines

Version 1 - 7 October 2026. **Candidate proof, not externally peer reviewed.**

Permanent archive: [DOI 10.5281/zenodo.23207765](https://doi.org/10.5281/zenodo.23207765).

The manuscript asserts that there exists a torsion-free word-hyperbolic group
that is not sofic and has a finite two-dimensional classifying space with a
locally CAT(-1) metric. It also asserts that some fixed nonidentity element
maps to the identity under every homomorphism to any sofic group.

The original marked-line construction, triangle wiring, interpolation identity,
fixed-prime rank comparison, exceptional-set method, and exact finite-quotient
rank obstruction are due to
[OpenAI family 252](https://github.com/openai/math/tree/adc7f1241b42e322a6451854ab7e4b4c146bf78a/preprints/a-torsion-free-hyperbolic-group-that-is-not-residually-finite-September-23-2026).
The new ingredient is a quantitative rank obstruction for arbitrary permutation
assignments, uniform in the permutation degree, that charges triangle errors
in normalized Hamming distance and rectangle fixed-point proportions. The
paper applies it to soficity and gives a separate five-dimensional realization
using the classical Lazebnik-Ustimenko-Woldar graph D(5,q).

The finite data are specified by a terminating search. The full presentation
at the stated parameters has not been materialized, and no practical runtime
bound is claimed. The paper establishes neither nonhyperlinearity nor failure
of linear soficity, and makes no property-(T) claim. The new arguments have
not been formally verified.

The derivation and manuscript received substantial assistance from OpenAI
language models. The human contact has not independently certified every
argument; the disclosure is included in the paper.

Read [the PDF](https://github.com/harjassand/marked-lines-nonsofic/releases/download/v1.0/main.pdf) or download [version 1.0](https://github.com/harjassand/marked-lines-nonsofic/releases/tag/v1.0). The standalone `main.tex` includes the bibliography and figure;
no additional source files are needed to compile it. With a standard TeX Live
or MiKTeX installation, run:

```sh
pdflatex main.tex
pdflatex main.tex
```

**Contact:** Harjas Sandhu - harjas.sandhu@student.uq.edu.au

To report an error, open a repository issue or email the contact, identifying
the manuscript version and the theorem, lemma, or equation concerned. Please
include the disputed step and, where possible, a counterexample or proposed
correction. Adversarial scrutiny and independent mathematical development
are welcome.

Reuse is permitted under Apache-2.0; see `LICENSE`. Preserve attribution to
the external mathematical sources.
