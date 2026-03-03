# Neutrosophic_Decision_Making_Models

[![DOI](https://zenodo.org/badge/1171779857.svg)](https://doi.org/10.5281/zenodo.18852634)

Reproducible SVNHFS benchmark code for the paper  
*A lattice structure on neutrosophic hesitant fuzzy sets with applications in decision making.*

## What this repository contains
- `Neutrosophic_Decision_Making_Models.ipynb`: reference implementation + experiments.
- `README.md`: this file.
- `LICENSE`.

## What the notebook does
- Implements the neutrosophic symmetric lattice operations and neutrosophic dominance functions
  (NDDF/NRDF and score-induced variants).
- Reproduces the manuscript tables by printing ready-to-paste LaTeX code.
- Runs robustness/stability analyses (Dirichlet perturbations of `λ` and `w`, leave-one-criterion-out,
  simplex grid sweeps) and reports ties-aware rank-agreement metrics (Kendall’s τ_b, Spearman’s ρ, Kendall’s W, etc.).
- Uses only the Python standard library (no NumPy/Pandas).

## Quick start
**Option A — Google Colab**
1. Open `Neutrosophic_Decision_Making_Models.ipynb` in Colab.
2. Run all cells.

**Option B — Local Jupyter**
1. Clone/download the repository.
2. Open the notebook with Jupyter and run all cells.

## Citation / DOI
- Concept DOI (all versions): https://doi.org/10.5281/zenodo.18852634
- Version DOI (v1.0.0): https://doi.org/10.5281/zenodo.18852635
