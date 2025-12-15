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

The `gridsearch.npz` file probably stores the results of a grid search over hyperparameters for one of the models.
