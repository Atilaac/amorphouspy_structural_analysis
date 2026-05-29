<p align="center"><img src="logo.png" alt="amorphouspy" width="260"></p>

# Structural Analysis of Oxide Glasses (amorphouspy)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Atilaac/amorphouspy_structural_analysis/HEAD?labpath=example.ipynb)

Complete structural analysis workflow for atomistic glass structures using **amorphouspy**.

**Tools covered:**

| Tool | What it measures |
|---|---|
| `compute_rdf` | Partial g(r) + cumulative coordination number CN(r) |
| `compute_coordination` | Coordination number histogram per element |
| `compute_qn` | Q⁰–Q⁴ species distribution (bridging oxygens per former) |
| `compute_network_connectivity` | Weighted average network connectivity ⟨n⟩ |
| `compute_angles` | Bond angle distribution for any triplet |
| `compute_structure_factor` | Total and partial S(q) — neutron or X-ray |
| `compute_guttmann_rings` | Guttman primitive ring-size distribution |
| `compute_cavities` | Void volumes, surface areas, and shape statistics |
| `visualize_cavities` | Interactive 3-D cavity rendering |
| `analyze_structure` | Single-call workflow running all of the above |
| `plot_analysis_results_plotly` | Interactive dashboard of all results |

**Example structure:** `data/SiONa_25.extxyz` — 25 mol% Na₂O · 75 mol% SiO₂ sodium silicate glass, ~10 000 atoms.

## Requirements

```
amorphouspy
```
