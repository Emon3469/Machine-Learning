# Machine Learning Notebooks

A small workspace with two Jupyter notebooks for experimenting with machine learning concepts and workflows.

## Contents
- [machine_learning.ipynb](machine_learning.ipynb): Main notebook covering core ML steps (data prep, modeling, evaluation).
- [machine_learning_1.ipynb](machine_learning_1.ipynb): Companion notebook with additional experiments or variations.

## Prerequisites
- Python 3.9+ (3.10 recommended)
- Jupyter Notebook or JupyterLab (or VS Code with the Python + Jupyter extensions)
- Common ML libraries (install as needed): NumPy, pandas, scikit-learn, matplotlib, seaborn

## Quick Start (VS Code)
1. Open this folder in VS Code.
2. Open either notebook: [machine_learning.ipynb](machine_learning.ipynb) or [machine_learning_1.ipynb](machine_learning_1.ipynb).
3. Select a Python interpreter when prompted.
4. Run cells top-to-bottom and adjust as needed.

## Environment Setup (Windows)
### Option A: `venv`
```powershell
python -m venv .venv
.\.venv\Scripts\Activate
python -m pip install --upgrade pip
pip install notebook numpy pandas scikit-learn matplotlib seaborn
```
Start Jupyter:
```powershell
python -m notebook
```

### Option B: Conda
```powershell
conda create -n ml python=3.10
conda activate ml
conda install -c conda-forge notebook numpy pandas scikit-learn matplotlib seaborn
```
Start Jupyter:
```powershell
jupyter notebook
```

## Data & Configuration
- If the notebooks read local datasets, place files in a `data/` folder and update paths accordingly.
- Set random seeds in notebooks for reproducible results if needed.

## Tips
- Use VS Code's variable explorer (Jupyter) for quick inspection.
- Save results: Export the notebook to HTML via the VS Code command palette or Jupyter UI.
- If you encounter missing packages, install them in the active environment and re-run the kernel.

## Project Status
This workspace is intended for learning and experimentation. Feel free to extend the notebooks, add a `requirements.txt`, and organize datasets under `data/`.
