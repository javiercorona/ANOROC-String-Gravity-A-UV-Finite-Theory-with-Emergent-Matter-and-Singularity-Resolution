# ANOROC-String Gravity
**A UV-finite modified gravity theory with string-derived matter and singularity resolution.**

## Key Features
- **Curvature Regularization**: Exponential cutoff `f(K) = 1 - exp(-βK/K_max)` resolves singularities.
- **Quantum Backreaction**: Term `V_μν` from string vacuum fluctuations (`<0|T_μν|0>`).
- **Emergent Matter**: Stress-energy tensor `T_μν^(string)` derived from Nambu-Goto action.

## Repository Structure
- `/src`: LaTeX source for the paper (`anoroc_paper.tex`).
- `/numerics`: Python scripts for solving `f(K)` cosmology (e.g., bounce solutions).
- `/data`: Sample outputs (GW ringdown profiles, LHC constraints).

## Requirements
- LaTeX (for compilation)
- Python 3.8+ (for numerics; requires `numpy`, `scipy`, `matplotlib`)

## Usage
1. Compile paper:
   ```bash
   pdflatex anoroc_paper.tex
