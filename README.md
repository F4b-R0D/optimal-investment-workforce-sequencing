# Optimal Investment Sequencing

A reproducible **ex ante investment-planning and operations-research project** for selecting the timing and scale of investments under labour, capacity, budget, and project constraints.

## Core idea

The project links an investment pipeline to sectoral and occupational labour demand and then optimizes the timing and scale of projects.

```
Project pipeline
    ↓
Investment by year and sector
    ↓
Input–Output model
    ↓
Employment by NAICS
    ↓
NAICS–NOC occupational mapping
    ↓
Occupational labour demand
    ↓
Labour supply / capacity constraints
    ↓
Optimal project timing and scale
```

## Research objective

Find the timing and magnitude of investments that produce a smoother and more sustainable employment path for strategic occupations while respecting project, labour, fiscal, and infrastructure constraints.

Initial applications may focus on electricians, trades, operators, engineers, and other occupations relevant to remote and northern development.

## Computational workflow

The project is **Jupyter-first**. Jupyter Notebook / JupyterLab is the primary environment for data construction, exploratory analysis, model prototyping, scenario analysis, optimization runs, and reproducible results.

Reusable functions should migrate from notebooks into the `src/` modules as the project matures.

## Repository structure

- `data/raw/` — original source data
- `data/interim/` — cleaned or harmonized intermediate data
- `data/processed/` — analysis-ready datasets
- `src/io/` — input–output calculations
- `src/occupations/` — NAICS–NOC mapping and occupational demand
- `src/labour_supply/` — labour-force and occupational supply paths
- `src/optimization/` — optimization model and constraints
- `src/scenarios/` — alternative investment and policy scenarios
- `notebooks/` — reproducible Jupyter notebooks
- `outputs/figures/` — figures
- `outputs/tables/` — tables
- `outputs/model_runs/` — optimization results
- `docs/` — methodology notes and research design
- `references/` — literature notes and source documentation
- `tests/` — validation and unit tests

## Planned model components

1. Investment project database
2. Input–Output employment multipliers
3. NAICS–NOC occupational staffing matrix
4. Occupational labour-supply trajectories
5. Project timing and scale decision variables
6. Workforce, budget, precedence, and capacity constraints
7. Objective functions for employment smoothing, shortages, FIFO reliance, and economic value
8. Scenario and sensitivity analysis

## Reproducibility

The preferred workflow is:

1. raw data ingestion in Jupyter;
2. harmonization and validation;
3. reusable transformations in `src/`;
4. scenario construction;
5. optimization;
6. export of figures, tables, and model runs.

## License

This project is released under the **MIT License**. See `LICENSE`.

## Status

Early-stage research and model development.
