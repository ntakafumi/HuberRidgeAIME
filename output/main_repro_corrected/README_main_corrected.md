# HuberRidgeAIME corrected main reproducibility outputs

Pipeline version: `main_corrected_inverse_map_2026-08-31_v2`

## Scientific correction
All AIME-family estimators in this release solve `X ≈ Y A^T`.  Huber residuals are row-RMS input-space residuals.  Coefficient norm is reported only as a regularization diagnostic.

## Division of responsibility between notebooks
- `HuberRidgeAIME_Main_Reproducibility_CORRECTED.ipynb`: dataset audit, corrected clean benchmark, all-method controlled stress, missing-data sensitivity, runtime, and core artifacts.
- `HuberRidgeAIME_Reviewer5_FullyCorrected_Experiments_FINAL.ipynb`: known-ground-truth faithfulness, focused HRA-versus-RidgeAIME experiments, lambda/delta sensitivity, LIME/TreeSHAP stress comparison, and spectral diagnostics.

The previous main-analysis implementation must not be used for current-manuscript numerical results.
