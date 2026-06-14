# Philosophy → Boltzmann

> A philosophical and mathematical derivation of the **Fully Connected Neuron Model** — from first principles to the Boltzmann distribution.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-4f8eff?style=flat-square&logo=github)](https://benyaminmahdavifar.github.io/philosophy-to-boltzmann/docs/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Notebook](https://img.shields.io/badge/Jupyter-notebook-orange?style=flat-square&logo=jupyter)](Fully_Connected_Neuron_Model_and_the_Complete_Pentagon.ipynb)

---

## Overview

This repository presents the idea that **abandoning layered network structure** in favour of a fully connected graph (complete graph **K_n**) is not merely an architectural choice — it is a philosophical necessity if the goal is **maximum information construction**.

The derivation proceeds in three stages:

1. **Philosophy** — what a neuron *does* and why it needs full connectivity
2. **Structure** — the complete pentagon (K₅) as a visual and mathematical anchor
3. **Convergence** — why this architecture naturally implements the Boltzmann distribution

---

## Key Results

| Quantity | Formula |
|---|---|
| Total edges | n(n−1)/2 |
| Directed exchange capacity | n(n−1) |
| Per-neuron I/O cap | n−1 |
| Residual inputs (remove 1 node) | (n−1)² |

The network learns both **discrimination among data** and **higher-order statistical relationships** — an advantage over unsupervised models like SOM that lack an explicit probability distribution.

---

## Contents

```
├── docs/
│   └── index.html          # Scientific dashboard (GitHub Pages)
├── index.html              # Root redirect → docs/
└── Fully_Connected_Neuron_Model_and_the_Complete_Pentagon.ipynb
```

---

## Live Site

**[benyaminmahdavifar.github.io/philosophy-to-boltzmann/docs/](https://benyaminmahdavifar.github.io/philosophy-to-boltzmann/docs/)**

Interactive features:
- Hover nodes on the K₅ pentagon to inspect connectivity
- Adjust temperature T to see how the Boltzmann distribution changes
- Full mathematical derivation with MathJax rendering

---

## Setup — GitHub Pages

1. Go to **Settings → Pages** in this repository
2. Set **Source** to `main` branch, folder **/ (root)**
3. Save — the site deploys in ~60 seconds

---

## Author

**Benyamin Mahdavifar** · [github.com/BenyaminMahdavifar](https://github.com/BenyaminMahdavifar)
