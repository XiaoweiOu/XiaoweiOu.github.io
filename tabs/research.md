---
title: Research
---

## Neural Quantum States and Optimization for the Quantum Sign Problem
*Sep. 2022 – Sep. 2024*

- Diagnosed why standard stochastic reconfiguration fails on frustrated magnets:
  the phase network trains much more slowly than the amplitude network, so
  Monte Carlo samples collapse and optimization stalls in a local minimum.
- Developed a modified stochastic reconfiguration (natural-gradient) optimizer
  that evolves the amplitude and phase networks with separate step sizes,
  learning complex wavefunctions with no pretraining or imposed sign priors.
- Reached energies within 0.01% of the exact value at *J*<sub>2</sub>/*J*<sub>1</sub> = 0
  and 0.7% at the maximally frustrated point *J*<sub>2</sub>/*J*<sub>1</sub> = 0.5
  on a periodic 6 × 6 lattice, using only 2,745 parameters.

Paper: [*Phys. Rev. B* **112**, 165122 (2025)](https://arxiv.org/abs/2510.02051)

## Deep Neural Backflow for Strongly Correlated Electrons
*Sep. 2023 – Sep. 2025*

- Co-developed a multi-determinant neural backflow wavefunction for the 2D
  Hubbard model, exploiting low-rank structure shared across determinants for
  ~10× faster training iterations (4 × 16 lattice, 256 determinants).
- Reached ground-state energies within 0.45% of auxiliary-field quantum Monte
  Carlo on lattices up to 10 × 10 at half filling, and reproduced the
  intertwined charge and spin stripe order at 1/8 hole doping.
- Built diagnostics (Gram matrices, singular-value spectra, PCA) showing that a
  deeper backflow network, more than adding determinants, improves accuracy and
  captures the sign structure with fewer dominant principal components.

Preprint: [arXiv:2609.26544](https://arxiv.org/abs/2609.26544)

## Electron–Phonon Coupled Systems with Neural Quantum States
*Jan. 2025 – present*

- Extending neural quantum states to coupled fermion–boson systems
  (2D Su–Schrieffer–Heeger model, bond-coupled polarons), where standard
  neural-network wavefunctions struggle to capture the effects of
  electron–phonon coupling.
- Running parameter sweeps over phonon frequency and electron–phonon coupling
  strength in bond-coupled polaron models, benchmarking variational energies
  against published results, in collaboration with researchers at the
  Flatiron Institute.
