# Optimal Investment Sequencing

A reproducible research project for ex ante investment planning under labour, capacity, budget, and timing constraints.

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

## Repository structure

- `data/raw/` — original source data
- `data/interim/` — cleaned or harmonized intermediate data
- `data/processed/` — analysis-ready datasets
- `src/io/` — input–output calculations
- `src/occupations/` — NAICS–NOC mapping and occupational demand
- `src/labour_supply/` — labour-force and occupational supply paths
- `src/optimization/` — optimization model and constraints
- `src/scenarios/` — alternative investment and policy scenarios
- `notebooks/` — exploratory analysis and prototypes
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

## Status

Early-stage research and model development.
