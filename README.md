# Irreducibility proof for the first cuboid polynomial \(P_{a,u}(t)\)
This repository contains a complete proof that the degree-8 even **cuboid polynomial**  
  
![P_{a,u}(t)](https://latex.codecogs.com/svg.latex?P_{a,u}(t)=t^{8}+6(u^{2}-a^{2})t^{6}+(a^{4}-4a^{2}u^{2}+u^{4})t^{4}-6a^{2}u^{2}(u^{2}-a^{2})t^{2}+a^{4}u^{4})
  
is **irreducible** in ![Z[t]](https://latex.codecogs.com/svg.latex?\mathbb{Z}[t]) for all coprime integers ![a ≠ u > 0](https://latex.codecogs.com/svg.latex?a%20\ne%20u%20%3E%200).

## Abstract
The proof systematically excludes all possible degree-8 factorizations. The arguments rely on:

- **Gauss’s lemma** for primitivity and monicity,  
- **parity and involution symmetry**,  
- **\(p\)-adic valuations** (2-adic and 3-adic analysis),  
- **a discriminant obstruction** for the final even quadratic divisor case.  

Together, these tools establish that no nontrivial factorization exists, proving full irreducibility.

## Context
This polynomial arises in the study of the **first cuboid conjecture**, related to the search for a *perfect cuboid* (Euler brick with integer face diagonals and space diagonal).  
See the [Wikipedia article on Euler bricks – Cuboid conjectures](https://en.wikipedia.org/wiki/Euler_brick#Cuboid_conjectures) for background.

## Preprint
The full compiled PDF is available [here](v3/Cuboid_conjecture_1.pdf) (latest version).

## Versions
Here is history of changes and results.

| Version | Case E | Case C | 4 + 4 | 2 + 6 |
|:-------:|:------:|:------:|:-----:|:-----:|
| [Version 1](v1/Cuboid_conjecture_1.pdf) | ✔️ | ✍️ | ❌ | ✔️ |
| [Version 2](v2/Cuboid_conjecture_1.pdf) | ✔️ | ❌ | ⚠️ | ✔️ |
| [Version 3](v3/Cuboid_conjecture_1.pdf) | ✔️ | ✔️ | ⚠️ | ✔️ |

**Notation:**  
✔️ — absolutely correct  
❌ — incorrect or contains fatal flaws  
✍️ — incomplete or draft  
⚠️ — contains edge cases or exceptions

## Author
Valery Asiryan, 2025  
asiryanvalery@gmail.com

## Feedback
If you find a mistake in my proof or notice a gap in the reasoning, please let me know — I will be grateful for your feedback and corrections.
