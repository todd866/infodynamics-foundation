# A Thermodynamic Foundation for the Second Law of Infodynamics

**Deriving Vopson's empirical law from stochastic thermodynamics.**

## Overview

Vopson & Lepadatu (2022) observed that information entropy in physical systems decreases over time, with symmetric states representing minimum information entropy. This paper provides the thermodynamic mechanism: maintaining asymmetric, low-dimensional structure requires continuous work input. Without this energy expenditure, systems relax toward symmetric equilibrium.

The key equation is the **geometric maintenance bound**:

$$W_{\mathrm{diss,min}} \geq k_B T \bigl(\ln 2 \cdot \Delta I + C_\Phi\bigr)$$

where $\Delta I$ is information removed and $C_\Phi$ is the geometric contraction cost (Jacobian of the projection map).

## Key Results

- **Structure-information** $I_{\mathrm{struct}} = D_{\mathrm{KL}}(p \| p_{\mathrm{iso}})$ reconciles the two second laws: thermodynamic entropy increases in the bath while structure-information decreases in the system
- Symmetric states require **zero maintenance power**—they are thermodynamic attractors
- Asymmetric states require **continuous work input** scaling with $C_\Phi$ and diffusion rate
- The second law of infodynamics emerges as a shadow of the second law of thermodynamics

## Repository Contents

```
├── paper/
│   └── ipi_infodynamics_submission.pdf   # Manuscript
├── src/
│   └── make_figures.py                   # Figure generation code
└── figures/
    ├── fig1_geometric_maintenance.pdf    # Schematic of the bound
    └── fig2_dimensional_relaxation.pdf   # Simulation results
```

## Running the Code

```bash
python3 src/make_figures.py
```

Requires: `numpy`, `matplotlib`

## Paper

**Title:** A Thermodynamic Foundation for the Second Law of Infodynamics
**Author:** Ian Todd
**Status:** Under review at IPI Letters

## Citation

```bibtex
@article{todd2025infodynamics,
  author = {Todd, Ian},
  title = {A Thermodynamic Foundation for the Second Law of Infodynamics},
  journal = {IPI Letters},
  year = {2025},
  note = {Under review}
}
```

## License

MIT
