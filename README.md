# DFT Calculations for Copper (Cu) using Quantum ESPRESSO

This repository contains Density Functional Theory (DFT) calculations for bulk Copper (Cu) performed using the Quantum ESPRESSO suite. The goal is to keep the workflow **reproducible**: input files used to run calculations, final outputs that validate results, and structure files that can be visualized.

---

## Overview
This project demonstrates a standard DFT workflow for a metallic system:
- Preparing Quantum ESPRESSO input files
- Running **relaxation** calculations 
- Extracting final values such as optimized geometry and total energy
- Visualizing the resulting structure using common tools

---

## Software and Method
- **Code:** Quantum ESPRESSO (`pw.x`)
- **Method:** Plane-wave pseudopotential DFT
- **Exchange–correlation:** LDA (as used in the provided inputs)
- **System:** Bulk Copper (Cu)

---

## What’s Included
- QE input files (`.in`) used for calculations
- QE output files (`.out`) from successful runs
- A structure file (`.xsf`) for direct visualization in XCrySDen/VESTA

---

## Repository Structure
- `inputs/` – Quantum ESPRESSO input files (`.in`) used to run calculations  
- `outputs/` – Output files (`.out`) from successful QE runs (final/clean runs only)  
- `structures/` – Structure/geometry files for visualization (e.g., `.xsf`)  
- `plots/` – Post-processing or visualization data (optional)  

---

## How to Run (Quantum ESPRESSO)

```bash
pw.x < inputs/cu_lda.relax.in > outputs/cu_lda.relax.out

