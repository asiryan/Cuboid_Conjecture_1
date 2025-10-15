# Irreducibility proof of the cuboid polynomial P_{a,u}(t)
This repository contains a complete proof that the degree-8 even **cuboid polynomial**  
  
![P_{a,u}(t)](https://latex.codecogs.com/svg.latex?P_{a,u}(t)=t^{8}+6(u^{2}-a^{2})t^{6}+(a^{4}-4a^{2}u^{2}+u^{4})t^{4}-6a^{2}u^{2}(u^{2}-a^{2})t^{2}+a^{4}u^{4})
  
is **irreducible** in ![Z[t]](https://latex.codecogs.com/svg.latex?\mathbb{Z}[t]) for all coprime integers ![a ≠ u > 0](https://latex.codecogs.com/svg.latex?a%20\ne%20u%20%3E%200).

## Abstract
The proof systematically excludes all possible degree-8 factorizations. The arguments rely on:

- **Gauss’s lemma** for primitivity and monicity,  
- **parity and involution symmetry**,  
- **\(p\)-adic valuations** (2-adic and 3-adic analysis),
- **an elliptic-curve reduction** with Mordell-Weil analysis,  
- **a discriminant obstruction** for the final even quadratic divisor case.  

Together, these tools establish that no nontrivial factorization exists, proving full irreducibility.

## Context
This polynomial arises in the study of the **first cuboid conjecture**, related to the search for a *perfect cuboid* (Euler brick with integer face diagonals and space diagonal).
See the [Wikipedia article on Euler bricks – Cuboid conjectures](https://en.wikipedia.org/wiki/Euler_brick#Cuboid_conjectures) for background.

## Preprints
History of changes and results of the main proof. Also available on [arXiv](https://arxiv.org/abs/2510.07643).  

| Version | Language       | Date       | Case E | Case C | 4 + 4 | 2 + 6 |
|:-------:|:----------:|:----------:|:------:|:------:|:-----:|:-----:|
| [Version 1](main/v1/Cuboid_conjecture_1.pdf) | EN | 2025-09-29 | ✔️ | ✍️ | ✍️ | ✔️ |
| [Version 2](main/v2/Cuboid_conjecture_1.pdf) | EN | 2025-10-04 | ✔️ | ❌ | ❌️ | ✔️ |
| [Version 3](main/v3/Cuboid_conjecture_1.pdf) | EN | 2025-10-05 | ✔️ | ✔️ | ❌ | ✔️ |
| [Version 4](main/v4/Cuboid_conjecture_1.pdf) | EN | 2025-10-05 | ✔️ | ✔️ | ⚠️ | ✔️ |
| [Version 5](main/v5/Cuboid_conjecture_1.pdf) | EN | 2025-10-08 | ✔️ | ✔️ | ⚠️ | ✔️ |
| [Version 6](main/v6/Cuboid_conjecture_1.pdf) | EN | 2025-10-08 | ✔️ | ✔️ | 🧩 | ✔️ |
| [Version 7](main/v7/Cuboid_conjecture_1.pdf) | EN | 2025-10-09 | ✔️ | ✔️ | ✔️ | ✔️ |
| [Version 8](main/v8/Cuboid_conjecture_1.pdf) | EN, [RU](main/v8/ru/Cuboid_conjecture_1_RU.pdf) | 2025-10-12 | ✔️ | ✔️ | ✔️ | ✔️ |

History of changes and results of the short proof. Also available on [arXiv](https://arxiv.org/abs/2510.11768).  

| Version | Language       | Date       | Case E | Case C | 4 + 4 | 2 + 6 |
|:-------:|:----------:|:----------:|:------:|:------:|:-----:|:-----:|
| [Version 1](short/v1/Cuboid_conjecture_1_short.pdf) | EN, [RU](short/v1/ru/Cuboid_conjecture_1_short_RU.pdf) | 2025-10-13 | ✔️ | ✔️ | ✔️ | ✔️ |

**Notation:**  
✔️ — correct  
🧩 — conjectural  
✍️ — incomplete / draft  
❌ — incorrect / fatal flaws  
⚠️ — unresolved edge cases  

## Verification
✔️ Checked with [GPT-5](https://chatgpt.com/) (Pro) and [Gemini-2.5-Pro](https://gemini.google.com/app) (Deep Think).

## Author
Valery Asiryan, 2025  
asiryanvalery@gmail.com

## Extra
[EllipticCurves](https://github.com/asiryan/EllipticCurves) — .NET library for studying and working with elliptic curves (with LMFDB integration).

## Feedback
If you spot an error, a gap, or a way to strengthen the proof, please let me know — I’d be grateful for any feedback or corrections.
