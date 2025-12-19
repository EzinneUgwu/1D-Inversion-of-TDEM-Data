# 1D-Inversion-of-TDEM-Synthetic-Data-from-Well-Log
This project generates synthetic time‑domain EM (TDEM) data from a 1D resistivity log, then inverts those data to recover a layered resistivity model. The goal is to test how well a VTEM‑style airborne TDEM system can recover the resistivity structure observed in Oil sands.

Project overview
Input: resistivity vs depth from a 300 m well, sampled every 2 m.

Forward model: 1D layered TDEM using a VTEM‑Plus‑style source–receiver geometry and 44 off‑time gates.

Synthetic data: computed responses with Gaussian noise.

Inversion: 1D layered inversion using a simpeg's smoothness‑regularized least‑squares formulation.

Output: recovered resistivity profile and comparison with the true log.
