# MSI-Data-Analysis
A simplified and anonymized Jupyter notebook demonstrating a microsatellite instability (MSI) analysis pipeline for cancer research.




# Microsatellite Instability (MSI) Analysis Pipeline – Demo

This repository contains a **sanitized and anonymized Jupyter notebook** that demonstrates a simplified version of a real-world pipeline used to detect **microsatellite instability (MSI)** in cancer research. The code was originally developed as part of a lab project at the University of Central Florida.

> **Disclaimer:** All data has been anonymized or simulated. This project does **not** contain any protected health information (PHI) or real patient data. It is shared solely for educational and portfolio purposes.

---

## What This Notebook Does

- Loads sample output files from an MSI detection tool (e.g., MSI Sensor)
- Parses each file to count the number of unstable loci
- Classifies samples as:
  - `MSI-High` (≥3 unstable loci)
  - `MSI-Low` (1–2 unstable loci)
  - `MSI-Stable` (0 unstable loci)
- Outputs a summary table and optionally generates visualizations

---

## Technologies Used

- **Python**
- **Pandas** for data handling
- **Matplotlib** for visual output
- **OS / Glob** for file I/O

---

