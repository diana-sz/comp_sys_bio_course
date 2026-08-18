# basiCO teaching notebooks

Jupyter notebooks for kinetic modeling and simulation using [basiCO](https://basico.readthedocs.io/en/latest/index.html), a Python interface to [COPASI](https://copasi.org/).

## Notebooks

- **`SIR.ipynb`** — A simple SIR epidemic model (Susceptible/Infected/Recovered). Covers building the model as a set of reactions, running deterministic and stochastic simulations, and scanning parameters like transmission and recovery rate.

- **`Enzyme_kinetics.ipynb`** — Basic enzyme kinetics: irreversible and reversible Michaelis-Menten kinetics, and substrate inhibition. Shows how to extract initial reaction rates from a simulation and reproduce the classic rate-vs-substrate-concentration curves.

- **`Transporter.ipynb`** — Carrier-mediated transport kinetics, including a custom (user-defined) rate law and a comparison to ordinary Michaelis-Menten kinetics. Reproduces the transporter-affinity results from [Bosdriesz et al. (2018)](https://doi.org/10.1038/s41598-018-23528-7), first with a small toy model and then with a realistic yeast glycolysis model.

- **`Oscillations.ipynb`** — Explores principles of biochemical oscillators based on the paper by Novák & Tyson [Design principles of biochemical oscillators
](https://doi.org/10.1038/nrm2530).


## Setup

```bash
conda env create -f environment.yml
conda activate <env-name>
```

  
To run the notebooks using Binder, click the button below

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/diana-sz/comp_sys_bio_course/main)


