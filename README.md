# TECF: Topological Error-Correcting Code Foam

Computational study of emergent spacetime-like geometry in quantum error-correcting codes.

## 📄 Paper

**Emergent Spacetime Geometry in Topological Quantum Error-Correcting Codes**  
**Author:** Chez Prefect with assistance from Claude (Anthropic) 
arXiv:[will add when available]  
Status: Submitted Oct 2025

## 🎯 Summary

This project simulates geodesic paths in emergent metrics derived from mutual information (MI) patterns in toric code lattices. The simulation demonstrates that information-optimal paths exhibit deflection when traversing spatially-varying entanglement landscapes.

### Key Findings

- **Geodesic deflection:** 2.54 ± 0.23× across lattice sizes (11-21 qubits)
- **Baseline contribution:** 2.28× from global MI gradient structure  
- **Defect contribution:** Additional 0-0.5× from localized topological defects
- **Curvature concentration:** 12-66× enhancement at defect sites (resolution-dependent)
- **Non-linear regime:** Deflection saturates while curvature diverges exponentially

### Control Experiments

Decomposition of geometric effects:
- Uniform field: 1.39× (no structure baseline)
- Random field: 1.33× (noise check)
- Smooth gradient: 2.28× (global structure only)
- With defects: 2.28-2.80× (configuration-dependent)

## 🚀 Quick Start

### Run in Google Colab (Easiest)

1. Click on `tecf_simulation.ipynb` above
2. Click "Open in Colab" button
3. Runtime → Run all
4. Results and figures generate automatically (~2 minutes)

### Run Locally
```bash
# Clone repository
git clone https://github.com/chez-ito/tecf-simulation.git
cd tecf-simulation

# Install dependencies
pip install numpy matplotlib scipy

# Run Jupyter notebook
jupyter notebook tecf_simulation.ipynb
