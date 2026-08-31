# Reviewer 5 manual revision checklist

## Major points
- [ ] Put the end-to-end HRA-versus-RidgeAIME outlier comparison in the main Results; use the fixed-black-box experiment as mechanism-isolating support.
- [ ] State that coefficient norm is a regularization diagnostic, not a quality score.
- [ ] Add the known-ground-truth support/direction/sign/clean-target recovery results and zero-operator control.
- [ ] Discuss why ridge can increase irrelevant-decoy mass and distinguish true decoys from correlated clones.
- [ ] Report lambda=0.01, delta=1.0, and the row-RMS residual definition; include lambda/delta sensitivity.
- [ ] Put a compact standard-LIME/native-TreeSHAP stress comparison in the main text.
- [ ] Report condition-cluster bootstrap 95% confidence intervals.

## Minor points
- [ ] Explain HAR's high robust-outlier cell rate using the heavy-tail/kurtosis diagnostics.
- [ ] Explain Australian Credit's high condition number using rank/spectrum and moderate correlations.
- [ ] Discuss Moore-Penrose, truncated SVD, and ridge as different spectral filters.
- [ ] Explain what lambda I_C adds even when the system is solved by SVD.
- [ ] Reduce the repeated 'not universally superior' statement to once in Results and once in Discussion.
- [ ] Correct Ref. 14 author formatting ('et al.' without '&').
- [ ] Correct the truncated author name in Ref. 17.
- [ ] Verify the author order/name formatting in Ref. 18.
- [ ] Capitalize 'Shapley' consistently.
- [ ] Use lambda I_C consistently.
- [ ] Explain that Table 2 uses median IRLS iterations and Table 4 uses mean iterations from a different experiment.
