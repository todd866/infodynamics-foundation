# A Thermodynamic Foundation for the Second Law of Infodynamics

**Deriving Vopson's empirical law from stochastic thermodynamics.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

## Overview

Vopson & Lepadatu (2022) observed that information entropy in physical systems decreases over time, with symmetric states representing minimum information entropy. This paper provides the thermodynamic mechanism: maintaining asymmetric, low-dimensional structure requires continuous work input. Without this energy expenditure, systems relax toward symmetric equilibrium.

**Key equation (geometric maintenance bound):**

$$W_{\mathrm{diss,min}} \geq k_B T \bigl(\ln 2 \cdot \Delta I + C_\Phi\bigr)$$

where $\Delta I$ is information removed and $C_\Phi$ is the geometric contraction cost.

## Key Results

- **Structure-information reconciliation**: $I_{\mathrm{struct}} = D_{\mathrm{KL}}(p \| p_{\mathrm{iso}})$ shows how thermodynamic entropy increases in the bath while structure-information decreases in the system
- **Symmetric attractors**: Symmetric states require zero maintenance power—they are thermodynamic attractors
- **Asymmetric maintenance cost**: Asymmetric states require continuous work input scaling with $C_\Phi$ and diffusion rate
- **Law derivation**: The second law of infodynamics emerges as a shadow of the second law of thermodynamics

## Running Simulations

```bash
cd src
python simulations.py        # Run all experiments
python make_figures.py       # Generate publication figures
```

Requires: `numpy`, `matplotlib`, `scipy`

## Paper

**A Thermodynamic Foundation for the Second Law of Infodynamics**

Todd, I. (2025). *IPI Letters* (minor revisions).

**Trilogy Part 1 of 3:**
- Part 2: [Black Hole Phenomenology from Observer-Relative Apertures](https://github.com/todd866/black-hole-aperture)
- Part 3: [Time, Mathematics, and the Relaxing Knot](https://github.com/todd866/cosmic-relaxation)

## Citation

```bibtex
@article{todd2025infodynamics,
  author  = {Todd, Ian},
  title   = {A Thermodynamic Foundation for the Second Law of Infodynamics},
  journal = {IPI Letters},
  year    = {2025},
  note    = {Minor revisions}
}
```

## License

MIT License
