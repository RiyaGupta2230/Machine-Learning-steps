
# Machine Learning Steps

This repository contains classroom labs and example datasets for introductory machine learning exercises.

Contents
- `Lab1.ipynb` .. `Lab6.ipynb` — Jupyter notebooks with lab exercises.
- `All_classifiers.ipynb` — Notebook comparing classifiers.
- `Iris.csv`, `advertising.csv` — Example datasets used by the notebooks.

Quick start (Windows PowerShell)
1. Create and activate a virtual environment (recommended):

   python -m venv .venv
   .\.venv\Scripts\Activate.ps1

2. Install Python dependencies:

   pip install -r requirements.txt

3. Launch Jupyter and open a notebook:

   python -m jupyter notebook

4. Open any `*.ipynb` file and run the cells.

Files added in this repo
- `.gitignore` — ignores `.ipynb_checkpoints/`, virtualenv folders, IDE settings, and common large dataset/file types so workbook folders stay clean.
- `requirements.txt` — lists common packages used by the notebooks (pandas, numpy, scikit-learn, jupyter, matplotlib, seaborn).

Notes
- For exact environment reproduction I can generate pinned versions from your current environment (a full `requirements.txt`) or an `environment.yml` for conda if you prefer.
- Small contributions: edit notebooks or add a new `notebooks/` folder; commit on a feature branch and open a PR.

Repository
- This repository is pushed to: https://github.com/RiyaGupta2230/Machine-Learning-steps

If you want, I will also create a short CONTRIBUTING.md and a license file next.
