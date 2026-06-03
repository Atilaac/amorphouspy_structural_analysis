<p align="center">
  <img src="logo.png" alt="amorphouspy logo" width="400"/>
</p>

# Structural Analysis of Oxide Glasses (amorphouspy)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Atilaac/amorphouspy_structural_analysis/HEAD?labpath=example.ipynb)

Demonstrates a complete structural analysis workflow for atomistic oxide glass structures using **amorphouspy**.

## Installation

```bash
# Install amorphouspy (from the amorphouspy repo)
cd /path/to/amorphouspy
pixi install

# Or with pip
pip install amorphouspy
```

## Run the workflow

```bash
jupyter lab
# open example.ipynb and run all cells
```

## What the notebook does

| Step | Description |
|------|-------------|
| 1 | Load a glass structure from `.extxyz` |
| 2 | Compute partial radial distribution functions g(r) |
| 3 | Compute coordination number distributions |
| 4 | Compute Q0–Q4 species distribution and network connectivity |
| 5 | Compute bond angle distributions (O-Si-O, Si-O-Si) |
| 6 | Compute total and partial structure factor S(q) — neutron or X-ray |
| 7 | Compute Guttman primitive ring-size distribution |
| 8 | Compute cavity volumes, surface areas, and shape statistics |
| 9 | Visualise cavities in 3D (Plotly) |
| 10 | Run full analysis with `analyze_structure` |
| 11 | Interactive dashboard with `plot_analysis_results_plotly` |

**Example structure:** `data/SiONa_25.extxyz` — 25 mol% Na₂O · 75 mol% SiO₂ sodium silicate glass, ~10 000 atoms.

## Requirements

```
amorphouspy
```

See the [documentation](https://glasagent.github.io/amorphouspy/) for more detail.
