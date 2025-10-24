# AES-128 CPA / DPA (Notebooks)

Two Jupyter notebooks demonstrating Correlation Power Analysis (CPA) and Differential Power Analysis (DPA) on AES-128, from trace loading to key byte recovery.

## Contents
- `file1_AES_DPA.ipynb` — DPA pipeline (selection function, hypothesis, grouping, distinguisher).
- `file2_AES_CPA.ipynb` — CPA pipeline (HW/HD leakage models, correlation, key rank insight).
- `images/` — figures exported from the notebooks.
- `data/` — **not committed**. Put your traces here (e.g., numpy arrays / CSV).  
  You may also use any public trace set compatible with the notebooks.

## Quick start
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook

