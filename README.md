

# 🪨 PETROLOG-PRO // Well Log Evaluator

An interactive, browser-based deterministic well log interpretation and quick-look petrophysics dashboard.

## 🚀 Live Demo
[Launch PETROLOG-PRO Live](https://Hariths-05.github.io/well-log-evaluator/)

## ⚡ Features
- **Multi-Track SVG Visualization:** Gamma Ray (GR), Deep Resistivity (Res), Porosity & Neutron-Density Crossover ($NPHI/\rho_b$), Water Saturation ($S_w$), and Net Pay Flags.
- **Dynamic Interpretation Engine:** Real-time calculation of $V_{\text{sh}}$, $\Phi_e$, Archie $S_w$, and Net-to-Gross (NTG).
- **Custom Depth Intervals:** Supports arbitrary intervals with automatic depth axis rescaling.
- **Advanced Raw Data Editor:** Direct copy-paste and injection for custom tabular well data.
- **Multi-Theme Support:** Dark Cyber, Obsidian OLED, and Modern Light interfaces.
- **Export Capabilities:** One-click CSV export of interpreted petrophysical curves.

## 📐 Petrophysical Model
- **Shale Volume:** Linear Gamma Ray Index
- **Porosity:** Density Porosity corrected for shale volume
- **Saturation:** Archie Equation ($S_w = \sqrt[n]{\frac{a \cdot R_w}{\Phi_e^m \cdot R_t}}$)
- 
