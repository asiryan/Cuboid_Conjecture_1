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
The full compiled PDF is available [here](main/v7/Cuboid_conjecture_1.pdf) (latest version).

## Versions
Here is history of changes and results.

| Version | Date       | Case E | Case C | 4 + 4 | 2 + 6 |
|:-------:|:----------:|:------:|:------:|:-----:|:-----:|
| [Version 1](main/v1/Cuboid_conjecture_1.pdf) | 2025-09-29 | ✔️ | ✍️ | ✍️ | ✔️ |
| [Version 2](main/v2/Cuboid_conjecture_1.pdf) | 2025-10-04 | ✔️ | ❌ | ❌️ | ✔️ |
| [Version 3](main/v3/Cuboid_conjecture_1.pdf) | 2025-10-05 | ✔️ | ✔️ | ❌ | ✔️ |
| [Version 4](main/v4/Cuboid_conjecture_1.pdf) | 2025-10-05 | ✔️ | ✔️ | ⚠️ | ✔️ |
| [Version 5](main/v5/Cuboid_conjecture_1.pdf) | 2025-10-08 | ✔️ | ✔️ | ⚠️ | ✔️ |
| [Version 6](main/v6/Cuboid_conjecture_1.pdf) | 2025-10-08 | ✔️ | ✔️ | 🧩 | ✔️ |
| [Version 7](main/v7/Cuboid_conjecture_1.pdf) | 2025-10-09 | ✔️ | ✔️ | ✔️ | ✔️ |

**Notation:**  
✔️ — correct  
🧩 — conjectural  
✍️ — incomplete / draft  
❌ — incorrect / fatal flaws  
⚠️ — unresolved edge cases  

## Verification
✔️ Checked with [GPT-5](https://chatgpt.com/) (Pro) and [Gemini](https://gemini.google.com/app) (Ultra).

## Author
Valery Asiryan, 2025  
asiryanvalery@gmail.com

## Feedback
If you spot an error, a gap, or a way to strengthen the proof, please let me know — I’d be grateful for any feedback or corrections.
