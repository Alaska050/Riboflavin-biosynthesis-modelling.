# Riboflavin Biosynthesis Modelling

This repository contains all computational modelling practicals completed as part
of an MSc Bioinformatics Modelling Cellular Systems module.

The practicals focus on the riboflavin biosynthesis pathway in *Bacillus subtilis*
and apply multiple modelling approaches to study pathway structure, dynamics,
and production potential.


### Practical 1 – Network Modelling
- Pathway and interaction network construction
- Cytoscape and STRING-based visualisation
- Qualitative analysis of pathway connectivity

### Practical 2 – Deterministic ODE Modelling (Antimony)
- Ordinary differential equation model of riboflavin synthesis
- Time-course simulation using Tellurium
- Analysis of metabolite dynamics

### Practical 3 – Constraint-Based Modelling (FBA)
- Flux Balance Analysis using OptFlux
- Biomass and riboflavin production reactions
- Flux constraints and wild-type simulations

### Practical 4 – Stochastic and Rule-Based Modelling
- Rule-based model implemented in BioNetGen
- Stochastic simulations (SSA)
- Comparison with deterministic behaviour

### Practical 5 – Kinetic Modelling (COPASI)
- SBML-based kinetic model
- Parameter exploration and simulation


## Repository Structure

The practicals contain:
- Jupyter notebooks (`.ipynb`)
- Antimony models (`.ant`)
- SBML files (`.sbml`)
- BioNetGen models (`.bngl`)


## How to Run the Notebooks

1. Install Python 3
2. Install required packages:
   ```bash
   pip install tellurium numpy matplotlib
