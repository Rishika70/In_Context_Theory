# Dynamics of Ontological Clarity

This repository contains the code and simulations for the paper:

**Rishika Rai (2025)**  
*Dynamics of Ontological Clarity: A Stochastic-Dynamical Framework for Mechanistic Interpretability and Alignment*

---

## Overview

We present a **stochastic-dynamical framework** to model how internal states of large models evolve. Unlike traditional posterior-tracking approaches, our model captures:

- **Smooth adaptation** via diffusion (gradual, Bayesian-like updates)  
- **Abrupt reorganization** via Poisson-driven jumps (rare, discrete transitions)

The framework links **mechanistic interpretability** and **alignment**, providing insight into:

- How circuits stabilize or reorganize  
- How landscapes can be engineered for safe interventions  

---

## Key Concepts

- **Double-Well Potential:** Models stable states (basins) and barriers for transitions.  
- **Diffusion:** Continuous Gaussian noise driving gradual adaptation.  
- **Jump Process:** Rare events that trigger sudden changes in internal representations.  
- **Ontological Clarity `O(t)`**: Measures stability and coherence of representations.  
- **Epistemic State `E(t)`**: Task-conditioned knowledge content.  
- **Landscape Engineering:** Shaping wells and barriers for alignment objectives.  

---

## Experiments

1. **FOC Dynamics:** Simulate coupled `E(t)` and `O(t)` dynamics under baseline and resonance regimes.  
2. **Double-Well Escape:** Compare diffusion-only and jump-augmented escape times.  
3. **Resonance Effects:** Study how periodic drives amplify jumps and trigger abrupt reorganization.  
4. **Metrics:** Mean escape time, transition rate, phase-change frequency, stability index.  

All experiments are implemented in Python and ready to run in Colab or local environment.

---

## Usage

- Run the provided Python scripts to reproduce simulations and plots.  
- Modify parameters for diffusion, jump rate, jump magnitude, or resonance to explore different regimes.  

---

## References

- Wurgaft et al. (2025) — *Dynamics of In-Context Learning*, arXiv:2506.17859  
- Kramers (1940) — Brownian motion in a field of force and the diffusion model of chemical reactions  
- Risken (1989) — *The Fokker–Planck Equation*, Springer
