# HuberRidgeAIME Reviewer 5 fully corrected experiment outputs

Pipeline version: `r5_final_inverse_map_complete_2026-08-31`

## Scientific corrections
- All AIME-family results use `X ≈ Y A^T`.
- Both the fixed-black-box contamination protocol and the original end-to-end stress protocol are reported.
- Huber weights use row-RMS input-space residuals.
- True irrelevant permutation decoys are separated from correlated clones.
- Coefficient norm is diagnostic only; ground-truth faithfulness is evaluated separately.
- Confidence intervals bootstrap condition clusters after averaging repeated seeds.
- Full baseline execution requires standard LIME; SHAP is native LightGBM TreeSHAP.
- Spectral diagnostics use `Y` and `sqrt(W)Y`.

## Code archive note
This ZIP contains generated outputs. Deposit this notebook itself (and preferably its executed copy) alongside the ZIP in the DOI-linked Zenodo release.
