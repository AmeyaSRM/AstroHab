# AstroHab

Exoplanet Habitability Analysis

AstroHab is a collection of Jupyter notebooks for exploring and analyzing exoplanet habitability. The notebooks demonstrate data loading, basic processing, visualization, and simple habitability metrics and models used to assess exoplanet environments.

Table of Contents

- About
- Repository Contents
- Requirements
- Setup
- Using the Notebooks
- Data
- Notes on Reproducibility
- Contributing
- License
- Contact

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

Using the Notebooks

- Each notebook contains explanatory text cells and code cells. Read the markdown cells for context before running code cells.
- Notebooks are intended to run on a standard laptop for small sample datasets. For larger datasets or long runs, consider using a workstation or cloud environment.
- Save checkpoints as you work to preserve results.

Data

- If a data/ directory is present, notebooks reference the files there. If not present, some notebooks may fetch example data from public catalogs or include small sample data embedded in the notebook.
- Verify file paths in the notebooks before running. Update paths if you place datasets in a different location.

Notes on Reproducibility

- Exact results depend on package versions and data updates. If precise reproducibility is required, pin package versions and note the dataset source and retrieval date.
- Random processes (e.g., train/test splits, stochastic algorithms) use a random seed when reproducibility is important; check notebook cells for seed settings.

Contributing

- Contributions are welcome. Please open an issue to discuss significant changes or bug fixes before submitting a pull request.
- When contributing notebooks or code, include a brief description, any new dependencies, and any data required to run the contribution.

License

This repository does not include an explicit license file. If you would like to specify a license, add a LICENSE file at the repository root. Until a license is added, assume standard copyright applies.

Contact

For questions about the notebooks or data, open an issue in this repository.

