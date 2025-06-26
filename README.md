# Dynamic Prediction of HIV-Related Incomplete Immune Reconstitution: A Multi-Center, Large Cohort Study Using Advanced Joint Modeling



## Abstract

**Background:** Incomplete Immune Reconstitution (IIR) affects 10–40% of people living with HIV (PLWH) receiving antiretroviral therapy (ART). Our aim was to develop an advanced, dynamic joint prediction system to enhance IIR risk stratification by generating continuously updated survival predictions using longitudinal clinical data.

**Methods:** In this retrospective, multi-centre study, we analysed data from 21,862 PLWH who initiated ART between 2003 and 2024 across 31 Chinese provincial-level administrative regions. We developed a Dynamic Joint Prediction System for IIR risk (DJPSIIR) using Bayesian shared-parameter multivariable joint modelling. The system incorporated longitudinal CD4+ T cell counts and CD4/CD8 ratios alongside clinical, biochemical, and immunological parameters. Model performance was evaluated using area under the receiver operating characteristic curve (AUROC), calibration metrics, and net benefits. We validated the model externally across the Ditan and You’an testing cohorts, and compared its performance against an expert-driven predictive model (EDPM), a blinded head-to-head comparative experiment, and 19 established machine learning algorithms.

**Findings:** The DJPSIIR demonstrated excellent discriminatory ability in the development cohort, with overall AUROCs of 0.912, 0.895, and 0.890 for prediction horizons of 5, 6, and 7 years, respectively. External validation confirmed comparable performance in both the Ditan (AUROCs: 0.900, 0.894, and 0.890) and You’an cohorts (AUROCs: 0.893, 0.895, and 0.891). The net benefit of the DJPSIIR consistently surpassed both “all intervention” and “no intervention” strategies across all cohorts. The DJPSIIR consistently outperformed the EDPM, clinical experts and 19 alternative machine learning algorithms and maintained robust predictive power across various ART regimen subgroups. Longitudinal CD4+ T cell count and CD4/CD8 ratio emerged as the primary predictors of IIR risk.

**Interpretation:** Our DJPSIIR offers a highly accurate, dynamic approach to predicting IIR risk in PLWH, surpassing expert-based predictive assessments and traditional models by incorporating longitudinal immune function trajectories. A clinical application tool was developed based on DJPSIIR that could facilitate the early identification of high-risk individuals, enabling timely and precise strategies to prevent IIR progression among PLWH.

## Requirements and Installation
To successfully run this project, you need the following environment and dependencies:

- **Operating System**: Windows, macOS, Linux
- **Python**: Version 3.9.7
- **R**: Version 4.3.3

First, clone project:
```bash
git clone git@github.com:FangLiu-Github/DJPSIIR.git
cd DJPSIIR
```
Next, download the transplant data from the Figshare Database and process it accordingly.
```bash
https://doi.org/10.6084/m9.figshare.29390141
```

