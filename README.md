# HuberRidgeAIME Reproducibility Package
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17172827.svg)](https://doi.org/10.5281/zenodo.17172827)

This repository provides the reproducibility package for the paper:

**HuberRidgeAIME: Robust Model-Agnostic Explanations under Outliers and Multicollinearity**

## Contents
- `HuberRidgeAIME_Repro_Final.ipynb`: a Jupyter notebook containing the full implementation of HuberRidgeAIME (HRA) together with baseline methods (AIME, HuberAIME, RidgeAIME, LIME, SHAP). Executing this notebook reproduces all tables and figures reported in the paper.
- `requirements.txt`: Python dependencies required to execute the notebook.
- `LICENSE`: License terms for research and educational use.
- `CITATION.cff`: Citation metadata for this package.

## Installation

We recommend Python 3.9 or newer. To set up a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt

##
	2.	Open HuberRidgeAIME_Repro_Final.ipynb.
	3.	Run all cells to regenerate:
	•	Table 1 (overall averages)
	•	Tables 2–4 (per-condition results)
	•	Table 5 (consistency analysis)
	•	Table 6 (synthetic grid comparisons with Wilcoxon tests, HL differences, effect sizes)
	•	Frontier plot figure (cost–performance analysis)

All outputs will be created in the working directory, and can be directly included in the LaTeX source of the paper.

## Data

We use only publicly available datasets:
	- UCI Breast Cancer Wisconsin (Diagnostic)
		- https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
	- UCI Australian Credit Approval
		- https://archive.ics.uci.edu/dataset/143/statlog+australian+credit+approval
	- UCI Human Activity Recognition (HAR)
		- https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones
No proprietary data are included in this package.

## License

This code and notebook are free to use, reproduce, and modify for academic research and educational purposes.
Commercial use is not permitted without prior written permission.
For commercial licensing inquiries, please contact: takafumi@eigenbeats.com.

## Contact

For questions, please contact:
Takafumi Nakanishi, Tokyo University of Technology
Email: takafumi@eigenbeats.com
