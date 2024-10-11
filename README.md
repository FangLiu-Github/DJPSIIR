# Dynamic Prediction of HIV-Related Incomplete Immune Reconstitution: A Multi-Center, Large Cohort Study Using Machine Learning Time Series Model



## Abstract

**Background:** Incomplete Immune Reconstitution (IIR) affects 10–40% of people living with HIV (PLWH) receiving antiretroviral therapy (ART). Our aim was to develop an advanced, dynamic artificial intelligence (AI) system to enhance IIR risk stratification by generating continuously updated survival predictions using longitudinal clinical data.

**Methods:** In this retrospective, multi-centre study, we analysed data from 21,862 PLWH who initiated ART between 2003 and 2024 across 31 Chinese provincial-level administrative regions. We developed a Dynamic Joint Prediction System for IIR Risk (DJPSIIR) using Bayesian shared-parameter multivariable joint modelling. The system incorporated longitudinal CD4+ T-cell counts and CD4/CD8 ratios alongside clinical, biochemical, and immunological parameters. Model performance was evaluated using dynamic area under the receiver operating characteristic curve (AUROC) and calibration metrics. We validated the model internally through resampling in the Xixi development cohort and externally across the Ditan and You'an testing cohorts. We also compared our system's performance against 19 established machine learning algorithms.

**Findings:** The DJPSIIR demonstrated excellent discriminatory ability in the development cohort, with overall AUROCs of 0.912, 0.895, and 0.890 for prediction horizons of 5, 6, and 7 years, respectively. External validation confirmed comparable performance in both the Ditan (AUROCs: 0.900, 0.894, and 0.890) and You'an cohorts (AUROCs: 0.893, 0.895, and 0.891). The DJPSIIR consistently outperformed 19 alternative machine learning algorithms and maintained robust predictive power across various ART regimen subgroups. Longitudinal CD4+ T-cell counts and CD4/CD8 ratios emerged as the primary predictors of IIR risk.

**Interpretation:** Our DJPSIIR offers a highly accurate, dynamic approach to predicting IIR risk in PLWH, surpassing traditional models by incorporating longitudinal immune function trajectories. This system could facilitate early identification of high-risk individuals, enabling timely and precise interventions to prevent IIR progression among PLWH.

## Requirements and Installation
To successfully run this project, you need the following environment and dependencies:

- **Operating System**: Windows, macOS, Linux
- **Python**: Version 3.9.7
- **R**: Version 4.3.3

First, clone project:
```bash
git clone git@github.com:FangLiu-Github/DJPSIIR.git
cd DJPSIIR

# install R Dependencies
install.packages(c("survival", "nlme", "splines", "JMbayes2", "timeROC", "ggplot2", "splitstackshape", "dplyr", "graphics", "grDevices"))
# install Python Dependencies
pip install pandas==1.3.3
pip install numpy==1.21.2
pip install scikit-learn==0.24.2
pip install joblib==1.0.1
```
Next, download the transplant data from the Zenodo Database and process it accordingly.
```bash
https://zenodo.org/records/13918025
```

