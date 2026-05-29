# Vibration-Based Structural Health Monitoring (SHM)

**Author:** Esmaeil Ghorbani  

---

## Overview

This repository serves as an introductory guide to *vibration-based Structural Health Monitoring (SHM)*.

Designed to break down complex structural dynamics into intuitive concepts, this guide connects the physics of vibrations to the inverse problem. You will learn how signal processing and structural dynamics combine to detect structural changes using real-world vibration data.

This content was prepared for a guest lecture in the *Structural Health Monitoring course (CEE 539) at Princeton University*.

---

Structural Health Monitoring (SHM) aims to:

- Monitor the condition of a structure  
- Detect potential damage  
- Evaluate its remaining service life  

In vibration-based SHM, damage is reflected as changes in:

- stiffness  
- mass  
- damping  

These changes affect the *measured vibration response*.

---

## What You Will Learn

This repository follows a complete SHM pipeline:

### 1. Forward (Direct) Problem

- Modeling vibrating systems (1-DoF and multi-DoF)
- Governing equations of motion
- Mass–spring–damper systems
- Mode shapes and natural frequencies
- Numerical solution of dynamic systems

---

### 2. Inverse Problem (Data-Based Analysis)

- Extracting system properties from measured data
- Correlation function
- Random Decrement (RD)
- Ibrahim Time Domain (ITD)

These methods estimate:

- Natural frequencies  
- Damping ratios  

from *output-only measurements*

---

### 3. Frequency-Domain Analysis

- Time domain → Frequency domain (FFT)
- Peak identification (peak picking)

> Peaks in the frequency spectrum correspond to *natural frequencies*

---

### 4. Real-World Application

- Full-scale bridge vibration analysis
- Monitoring system behavior over time
- Interpretation of frequency shifts

Examples:

- Frequency decrease → possible *stiffness reduction* (scour)
- Frequency increase → possible *environmental effects* (ice)

---

## Key Takeaway

> Structural changes → modify dynamic properties → change vibration features → detectable in data

- Data-based methods can *detect changes*
- Additional analysis is required to *quantify damage*

---

## Repository Structure

- `forward_problem/` → 1-DoF and multi-DoF modeling  
- `time_domain/` → Correlation, RD, ITD methods  
- `frequency_domain/` → FFT and peak picking  
- `case_study/` → Bridge data analysis  
- `notebooks/` → Jupyter demonstrations  

---

## References

### Books

- Chopra, A. K. — *Dynamics of Structures*  
- Inman, D. J. — *Engineering Vibration*  
- Clough, R. W., & Penzien, J. — *Dynamics of Structures*  
- Ewins, D. J. — *Modal Testing*  

---


### Papers

- Ghorbani, E., et al.  
  *Bridge pier scour level quantification based on output-only Kalman filtering*  
  Structural Health Monitoring, 21(5), 2116–2135  

- Ghorbani, E., et al.  
  *Hybrid output-only structural system identification using random decrement and Kalman filter*  
  Mechanical Systems and Signal Processing, 144 (2020): 106977  

---

## Citation

If you use this material:

- Cite this repository (if published)  
- Cite the associated papers above  

---

## Contact

- Email: ghorbani@princeton.edu
