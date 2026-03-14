# NMA Pro v8.0

**Browser-based network meta-analysis platform with 21 analytical workflows.**

## Quick Start
1. Open `nma-pro-v8.0.html` in Chrome, Firefox, or Edge
2. Click "Load Demo" to load the Thrombolytics dataset
3. Click "Run Analysis"

No installation required.

## Features
- **Frequentist NMA** (DL, REML, PM, fixed-effect)
- **Bayesian MCMC** (HMC, configurable chains)
- **Ranking** (P-scores, SUCRA, rank probabilities)
- **Consistency** (node-splitting, design-by-treatment)
- **CNMA** (component network meta-analysis)
- **C-STREAM** (transportability assessment)
- **CINeMA** (certainty in NMA)
- **GRADE** framework integration
- **Dose-response NMA** (Emax, cubic splines)
- **Meta-regression** with covariates
- **Publication bias** (Begg, PET-PEESE, selection models)
- **WebR in-browser validation** (metafor/netmeta)
- **Seeded PRNG** (xoshiro) for reproducibility
- **Export**: CSV, PNG, PDF, R code

## Validation
R validation against netmeta, metafor, meta packages. See `tests/nma_validation.R`.

## Citation
> Ahmad M, et al. NMA Pro v8.0. *F1000Research*. 2026. [DOI pending]

## License
MIT
