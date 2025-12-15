# Graph Learning Assignment

This repository contains the work for a graph learning assignment. The assignment explores various concepts in graph neural networks (GNNs), including implementing GNN models, training them on different datasets, and analyzing their performance.

## Folder Structure

```
.
├── 2_a.ipynb
├── 2_b.ipynb
├── 2_c_d_e.ipynb
├── assignment.pdf
├── data (ignored by Git)
├── GNN_tutorial.ipynb
├── gridsearch.npz
├── pyproject.toml
├── README.md
├── report
│   ├── figures
│   ├── references.bib
│   └── report.tex
├── tutorial.ipynb
└── uv.lock
```

## Assignment

The `assignment.pdf` file describes the tasks that were completed for this project. The solutions and implementations for these tasks can be found in the Jupyter notebooks:

- `2_a.ipynb`: Notebook for task 2a.
- `2_b.ipynb`: Notebook for task 2b.
- `2_c_d_e.ipynb`: Notebook for tasks 2c, 2d, and 2e.

The `GNN_tutorial.ipynb` and `tutorial.ipynb` are additional notebooks that were likely used for learning and exploration purposes.

## Report

The final report for this assignment is available as a PDF: `report/report.pdf`. The LaTeX source code for the report is in `report/report.tex`, with figures in `report/figures/` and references in `report/references.bib`.

## Data

The `data/` directory contains the datasets used for training and evaluating the GNN models. This directory is ignored by Git and will not be pushed to the remote repository. If you clone this repository, you will need to obtain the datasets separately or run the scripts that generate them.

- `data/Planetoid/Cora`: The Cora dataset, a citation network of scientific publications.
- `data/TUDataset/MUTAG`: The MUTAG dataset, a collection of graphs representing chemical compounds.

## Grid Search

The `gridsearch.npz` file stores the results of a grid search over hyperparameters for one of the models.

## Python Environment Setup

To run the Jupyter notebooks and reproduce the results, a specific Python environment is
required. The following steps outline the setup process using uv, a fast Python package installer.

1. Install uv: If not already installed, run the following command:

```bash
curl -Lsf https://astral.sh/uv/install.sh | sh
```

2. Create Virtual Environment: This project uses Python 3.13. From the project root,
create a virtual environment:

```bash
uv venv
```

uv will automatically detect the required Python version from the .python-version file.
3. Install Dependencies: Activate the environment and install packages using the sync
command:

```bash
uv pip sync
```

This command uses the pyproject.toml and uv.lock files to ensure a reproducible envi-
ronment. You can then start Jupyter Lab by running `jupyter lab`.
