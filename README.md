# QUBO Clustering

This project implements clustering as a **QUBO (Quadratic Unconstrained Binary Optimization)** problem.

The notebook includes:
- generation of synthetic balanced data,
- construction of a QUBO formulation for clustering,
- optimization with `dimod` and `neal` (`SimulatedAnnealingSampler`),
- evaluation using clustering metrics,
- an experiment on the Wine dataset.

## Requirements

- Python 3.13

## Create a virtual environment

### macOS / Linux

```bash
python3.13 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
### Windows

```bash
py -3.13 -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```
## Run the project

jupyter notebook QUBO-clustering.ipynb
