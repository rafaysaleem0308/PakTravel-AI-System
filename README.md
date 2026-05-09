# PakTravel AI System

PakTravel AI System is a single-notebook semester project that demonstrates how classic AI techniques can be applied to Pakistan's road travel domain. The notebook is intentionally self-contained: all analysis, models, visualizations, and the interactive dashboard live inside one file.

## Highlights

- Route planning with Uniform Cost Search, A\*, and weighted bidirectional search
- Rule-based traffic law reasoning using propositional logic ideas
- CSP-based bus scheduling with backtracking and MRV-style ordering
- Bus delay prediction using both scikit-learn and a NumPy neural network
- Traveller segmentation with K-Means clustering
- A lightweight `ipywidgets` dashboard for live interaction

## Repository Layout

- `PakTravel_AI_System.ipynb` - main notebook
- `README.md` - project overview and run instructions
- `.gitignore` - excludes local environments and notebook cache files
- `aima-python/` - bundled AIMA logic source used by the notebook
- `file.png`, `file2.png`, `file3.png` - supporting images in the workspace

## Requirements

The notebook is designed for Python 3.x with these packages:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `networkx`
- `scikit-learn`
- `ipywidgets`

The logic-based section loads AIMA directly from the included `aima-python` folder, so no separate AIMA installation is required.

## Quick Start

1. Open `PakTravel_AI_System.ipynb` in Jupyter Notebook or VS Code.
2. Run the setup cell first so the local dependencies and AIMA logic load correctly.
3. Execute the notebook from top to bottom.
4. Use the final dashboard cell to test the route planner, legal advisor, scheduler, delay predictor, and clustering views.

## What the Notebook Demonstrates

The notebook presents a complete academic-style AI workflow:

- Road network construction for Pakistani cities
- Shortest-path search with timing and node-expansion comparison
- A traffic-law reasoning demo with rule-based inference
- A bus scheduling CSP for route assignment
- Synthetic ANN training for delay prediction
- Customer segmentation with K-Means and visualization

## Notes

- The project is designed as a single notebook for ease of submission and presentation.
- The local `.venv` folder is intentionally excluded from version control.
- The bundled `aima-python` folder must remain in the repository for the logic cell to work offline.

## Status

The notebook and dashboard are built for demonstration and viva use, and the repository is ready for GitHub upload.
