# AstroHab

Exoplanet Habitability Analysis

AstroHab is a collection of Jupyter notebooks for exploring and analyzing exoplanet habitability. The notebooks demonstrate data loading, basic processing, visualization, and simple habitability metrics and models used to assess exoplanet environments.

About

This repository contains interactive analyses intended for researchers, students, and hobbyists interested in exoplanet habitability. The notebooks are meant to be read and run in order to reproduce the figures and results.

Repository Contents

- *.ipynb — Jupyter notebooks with analysis and visualizations
- data/ (optional) — example or input datasets used by the notebooks (if present)
- README.md — this file

Requirements

- Python 3.8 or newer
- Jupyter Notebook or JupyterLab
- Common scientific packages: numpy, pandas, matplotlib, seaborn, scipy
- Astrophysics and domain packages (used by some notebooks): astropy
- (Optional) scikit-learn for simple ML or clustering experiments

If a requirements.txt is not present, install the essentials manually:

```bash
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
.venv\Scripts\activate     # Windows (PowerShell)
python -m pip install --upgrade pip
pip install jupyter numpy pandas matplotlib seaborn scipy astropy scikit-learn
```

Setup

1. Clone the repository:

   git clone https://github.com/AmeyaSRM/AstroHab.git
   cd AstroHab

2. Start Jupyter:

   jupyter notebook

3. Open and run the notebooks in the browser. Work through them in the order provided if one notebook depends on outputs from another.


