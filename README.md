# Stochastic Analysis of Epidemic Dynamics via SIR Compartment Model

## Overview

This repository contains a stochastic epidemic modeling project using the susceptible-infectious-recovered compartmental framework. The analysis evaluates disease transmission and recovery under probabilistic assumptions and illustrates how uncertainty can influence epidemic trajectories and intervention effects.

## Repository

- **Repository name:** `STAT-6379-Final-Project`
- **Repository type:** Jupyter Notebook stochastic modeling repository
- **Repository link:** https://github.com/Agyemang1z/STAT-6379-Final-Project
- **Primary author:** Edmund Fosu Agyemang
- **Academic identifier:** ORCID: https://orcid.org/0000-0001-8124-4493

## Repository Contents

The public repository listing identifies the following files:

- `README.md`
- `Stochastic Project.ipynb`

## Research Objectives

- Implement a stochastic SIR model for epidemic dynamics.
- Compare Poisson and Binomial assumptions for transmission and recovery processes.
- Assess sensitivity to key epidemiological parameters.
- Explore the potential impact of interventions such as vaccination and social distancing.

## Analytical Workflow

1. Define SIR compartments and initial conditions.
2. Specify transition probabilities or event rates for infection and recovery.
3. Simulate epidemic trajectories under stochastic assumptions.
4. Compute summary measures such as peak infections and final epidemic size.
5. Conduct sensitivity analysis for transmission and recovery parameters.
6. Compare scenarios with and without public health interventions.

## Software Requirements

Recommended software and packages include:

- Python 3.10 or later
- Jupyter Notebook or JupyterLab
- numpy
- pandas
- matplotlib
- scipy

## Reproducibility Guide

Run the project from a clean working directory. The following commands provide a suggested starting point:

```bash
git clone https://github.com/Agyemang1z/STAT-6379-Final-Project.git
cd STAT-6379-Final-Project
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install numpy pandas matplotlib scipy jupyter
jupyter notebook "Stochastic Project.ipynb"
```

If file names include spaces, keep quotation marks around the file name when launching notebooks or scripts from the terminal.

## Expected Outputs

- Simulated epidemic curves
- Sensitivity analysis results
- Intervention scenario comparisons
- Figures for stochastic SIR interpretation

## Data Availability and Responsible Use

The data and code are provided for scholarly, educational, and reproducibility purposes. Users should verify the original data source, data license, and any use restrictions before redistribution or secondary analysis. When the dataset contains human, health, financial, or election-related information, results should be interpreted responsibly and reported with appropriate methodological caution.

## Suggested Citation

Agyemang, E. F. (2025). *Stochastic Analysis of Epidemic Dynamics via SIR Compartment Model* [Source code and data]. GitHub. https://github.com/Agyemang1z/STAT-6379-Final-Project

## Keywords

SIR model, Stochastic modeling, Epidemic dynamics, Poisson process, Binomial process, Public health intervention

## Disclaimer

This repository is intended to support reproducible research. The code and outputs should not be used as a substitute for professional clinical, financial, legal, electoral, or policy judgment.
