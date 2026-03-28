# DFT Calculations for Copper (Cu) using Quantum ESPRESSO

## 📌 Overview

This project performs **Density Functional Theory (DFT)** calculations for bulk Copper (Cu) using the **Quantum ESPRESSO** simulation suite.
The objective is to study the electronic structure and validate computational results through reproducible workflows.

---

## ⚛️ What is DFT?

Density Functional Theory (DFT) is a quantum mechanical modeling method used to investigate the electronic structure of materials.

---

## 🎯 Objectives

* Perform DFT simulations for bulk Copper (Cu)
* Analyze structural and electronic properties
* Maintain a reproducible workflow for simulations
* Store input, output, and structure files systematically

---

## 📂 Project Structure

```
├── input/          # Input files for Quantum ESPRESSO simulations
├── output/         # Output results from DFT calculations
├── structures/     # Crystal structure files (Cu lattice)
├── README.md
```

---

## 🛠️ Tools & Technologies

* Quantum ESPRESSO
* Density Functional Theory (DFT)
* Python (optional for post-processing)
* Linux/Unix environment

---

## ⚙️ Prerequisites

* Quantum ESPRESSO installed
* Basic knowledge of DFT and solid-state physics
* Linux terminal familiarity

---

## 🚀 How to Run

### 1. Navigate to input directory

```bash
cd input
```

### 2. Run Quantum ESPRESSO calculation

```bash
pw.x < input_file.in > output_file.out
```

### 3. Check results

Outputs will be generated in the `output/` folder.

---

## 📊 Key Outputs

* Total energy of the system
* Convergence behavior
* Electronic structure properties
* Optimized lattice parameters

---

## 🔍 Key Learnings

* Understanding of DFT workflow using Quantum ESPRESSO
* Handling input/output files for simulations
* Interpreting computational material science results

---

## 💡 Future Improvements

* Band structure and DOS (Density of States) analysis
* Visualization using tools like VESTA
* Automating workflows using Python scripts
* Extending to other materials

---

## 📬 Author

Kerat Panwar
