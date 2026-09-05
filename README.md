# Stochastic Differential Equations Lab

A Python notebook introducing simulation of Wiener processes and numerical solutions of stochastic differential equations.

## Covered Topics

- Simulation of multiple Wiener-process trajectories
- Visualization against the envelope `±sqrt(3t)`
- Exact simulation of geometric Brownian motion
- Euler–Maruyama approximation for

  ```text
  dX_t = b X_t dt + σ X_t dW_t,    X_0 = 1
  ```

- Pathwise comparison of the exact and approximate solutions
- Empirical mean-squared error analysis as the time grid is refined

## Contents

- `Lab1/Suleimanov_Lab_SDE_4_course.ipynb` — the complete lab notebook with implementations, experiments, and plots

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- NumPy
- pandas
- Matplotlib

Install and launch with:

```bash
python -m pip install jupyter numpy pandas matplotlib
jupyter notebook
```

Open the notebook and execute the cells from top to bottom. Random seeds are fixed in the exercises to make the numerical experiments reproducible.

## Status

Academic coursework archive focused on illustrating simulation and convergence concepts.
