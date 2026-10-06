# Jupyter Notebooks

This project uses Jupyter Notebook / JupyterLab as the main analysis environment.

Recommended notebook sequence:

1. `01_project_pipeline.ipynb` — investment-project database and annual spending paths
2. `02_input_output_model.ipynb` — IO transformations and employment by NAICS
3. `03_naics_noc_mapping.ipynb` — occupational staffing matrix and employment by NOC
4. `04_labour_supply.ipynb` — occupational labour-supply trajectories
5. `05_baseline_gaps.ipynb` — demand-supply gaps by occupation and year
6. `06_optimization_model.ipynb` — decision variables, constraints, and objective function
7. `07_scenarios.ipynb` — alternative investment and labour-market scenarios
8. `08_results.ipynb` — final figures, tables, and sensitivity analysis

Keep exploratory code in notebooks, but move stable reusable functions into `src/`.
