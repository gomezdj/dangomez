---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true

# --- Academic Metadata ---
authors: "Daniel J. Gomez, et al."
journal: ""
doi: ""
external_link: ""

# --- Stanford/Snyder Lab Context ---
lab: "Snyder Lab"
institution: "Stanford Genetics"
consortia: [] # e.g., ["HuBMAP", "HTAN", "MoTrPAC"]

# --- Computational Stack (Stanford Focus) ---
giotto_modules: [] # e.g., ["Giotto Suite", "Giotto Analyzer", "Giotto Visualizer"]
spatial_tech: []    # e.g., ["Xenium", "Visium", "CODEX"]
analysis_modality: "Spatial Multi-omics"

# --- [CRITICAL] Safety Net ---
tags: ["Giotto", "Stanford Genetics", "Spatial Biology"]
summary: ""
---

## Computational Workflow
This project utilized the **Giotto Suite** for:
- [ ] Spatial clustering
- [ ] Cell-type deconvolution
- [ ] Ligand-receptor interaction mapping
