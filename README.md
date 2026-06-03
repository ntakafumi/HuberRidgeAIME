# HuberRidgeAIME package
[![DOI](https://zenodo.org/badge/1257880530.svg)](https://doi.org/10.5281/zenodo.20520654)

This package contains the code and generated artifacts for the Scientific Reports revision of:

**HuberRidgeAIME: Robust Model-Agnostic Explanations under Outliers and Multicollinearity**

## What this package contains

```text
notebooks/HuberRidgeAIME_SciReports_Final_Repro.ipynb
requirements.txt
environment.yml
output/
  data/       CSV outputs, environment manifests, provenance metadata
  tables/     LaTeX tables for manuscript/supplement
  figures/    PNG figures for manuscript/supplement
  logs/       optional logs
```

All final outputs are intentionally stored under `./output/`.
There are no author-specific absolute paths.

## Recommended execution

Create an environment and run the notebook or script from the repository root.

```bash
python -m pip install -r requirements.txt
jupyter nbconvert --execute --to notebook --inplace notebooks/HuberRidgeAIME.ipynb
```

## Figure provenance

Figure/table provenance is recorded in:

```text
output/data/revision_figure_provenance.csv
output/tables/table_revision_figure_provenance.tex
output/revision_artifact_manifest.csv
```

These files identify the source CSV and generating function for each output artifact.
