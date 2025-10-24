# Zero-Metallicity Stellar Evolution and Nucleosynthesis (Population III)

This repository accompanies the research project *“Zero Metallicity Stars: Nucleosynthesis, Evolution and Fates of Massive Stars”* (Samuel Muthu, 2025).  
It contains simulation files, analysis scripts, and figures derived from detailed one-dimensional stellar models computed with the MESA code.

---

## Overview

This study investigates the **structure, evolution, and nucleosynthetic yields** of zero-metallicity (Population III) massive stars.  
Models span **10–20 M⊙** and **25 M⊙**, evolved up to **silicon burning** using the `mesa_128.net` nuclear network, Ledoux convection, and the Dutch mass-loss prescription.

Key focuses include:
- Convective behaviour and inter-convective zones (ICZ)
- Shell mergers and late-stage burning structures
- Core evolution on the \(T_c\)–\(ρ_c\) plane
- Remnant and supernova yield predictions

---

## ⚙️ Simulation Details

- **Code:** [MESA r24.03.01]
- **Composition:** \( X=0.75291,\ Y=0.24709,\ Z=0 \)
- **Nuclear network:** `mesa_128.net` (128 isotopes)
- **Convection criterion:** Ledoux  
- **Overshoot prescription:** Exponential (Herwig 2000)  
- **Mass-loss scheme:** Dutch (Vink et al. 2001; de Jager 1988)
- **Rotation:** neglected for computational efficiency

| Mass (M⊙) | Convective Boundary Mixing rate (f value) |
|------------|------|
| 10 | 3.4 |
| 11 | 3.7 |
| 12 | 4.0 |
| 13 | 4.3 |
| 14 | 4.6 |
| ≥15 | 5.0 |

---
## Main Results

- Emergence of **detached ICZs** following He exhaustion in all models  
- **Shell mergers** and convective coupling between burning zones in mid-mass stars  
- **Remnant transition** from neutron star to black hole at ~17–18 M⊙  
- **Primary isotope yields** (e.g., ¹²C, ¹⁶O, ²⁰Ne) increase monotonically with mass  
- **Secondary isotopes** (e.g., ¹³C, ¹⁴N, ²³Na) exhibit non-monotonic trends linked to convective-reactive shell mixing  

---
## Author

**Samuel Muthu**  
Keele University 
Email: _samuelmuthu2003@gmail.com_  
Supervisor: Dr Raphael Hirschi  

---
