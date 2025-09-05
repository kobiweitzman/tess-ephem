# Target Sheet — A

**Generated:** 2025-09-05

## Identifiers
- TIC: 119584412
- TOI: 1801.01

## Basic properties (TIC v8)
- Tmag: 9.85623
- Teff [K]: 3815.0
- R★ [R☉]: 0.545591
- Contamination ratio: 0.000276
- Crowding (≈1/(1+contam)): 0.999724

## TESS coverage
- Sectors (so far): 22, 49

## Why this target (auto)
R*~0.55 R☉; contam~0.00; crowding~1.00; Tmag~9.9

## Plan & status
- [x] Download PDCSAP (+ FFI fallback if needed)
- [x] Gentle detrend (1 d window)
- [ ] TLS + BLS (per-sector, stitched)
- [ ] Folded plot with model overlay
- [ ] Mid-times + linear ephemeris
- [ ] Vetting pass 1 (odd/even, secondary)
- [ ] Vetting pass 2 (centroids/diff image)
- [ ] TRICERATOPS FPP
- [ ] Injection–recovery spot check

## Quality & events (QA) — 2025-09-05
- S22 — PDCSAP, N_use=16,101/16,101 (frac_bad=0.00), CDPP(1 h)≈740 ppm, smooth long trend; no obvious large flares.
- S49 — PDCSAP, N_use=13,272/13,272 (frac_bad=0.00), CDPP(1 h)≈937 ppm, gentle curvature; no gross systematics.
- Both sectors look clean enough for folding; transit depth will be shallow, so stacking or careful binning will matter.
- Next actions: run fold/TLS per sector and stitched; start midtime extraction if a dip is seen.

## Notes
- Sensitivity concerns: shallow depth expected; use conservative flattening and mean/quantile binning.
- Crowding/contamination flags: essentially zero; aperture losses unlikely to be a blocker.
- Nearby brighter stars: none concerning in TIC; recheck in difference images during vetting.
