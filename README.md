# PakTravel AI System

PakTravel AI System is a single-notebook university project that demonstrates multiple AI techniques for Pakistan's road travel domain.

## What it includes

- Route planning with Uniform Cost Search, A*, and weighted bidirectional search
- A rule-based AI legal advisor using propositional logic concepts
- CSP-based bus scheduling with backtracking and MRV-style ordering
- Bus delay prediction with a scikit-learn MLP and a NumPy neural network
- Traveller clustering with K-Means
- A lightweight interactive dashboard built with `ipywidgets`

## Project Files

- `PakTravel_AI_System.ipynb` - main notebook
- `aima-python/` - local AIMA logic library used by the notebook
- `.venv/` - local Python environment used for development, not meant for version control

## Requirements

The notebook uses:

- Python 3.x
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `networkx`
- `scikit-learn`
- `ipywidgets`

The notebook also loads AIMA logic from the bundled `aima-python` folder.

## How to Run

1. Open `PakTravel_AI_System.ipynb` in Jupyter Notebook or VS Code.
2. Run the setup cell first.
3. Run the notebook cells in order from top to bottom.
4. Use the final GUI cell to interact with the project components.

## Notes

- The notebook is designed to be self-contained in one file.
- The local `aima-python` folder is included so the logic-based part works without a separate package install.
- The `.venv` folder should stay local and should not be pushed to GitHub.

## Project Status

The notebook includes all five major project parts and an interactive dashboard for demonstration.
