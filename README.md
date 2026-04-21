# Hi there 👋 I'm Z (they/them)

📊 I’m a **Senior at Pomona College**, majoring in **Mathematics & Statistics** with a minor in **Data Science**.  

🔍 I’m interested in Bayesian and causal inference, probabilistic modeling, and decision-focused statistics, with applied work in healthcare and baseball analytics.

## Current Projects

# Inference Without Data
### A Causal Transportability Framework for Ketamine Effects in TGD Populations
 
---
 
## Overview
 
This thesis develops a causal data fusion framework for estimating treatment effects when the target population is absent from existing clinical trials. The central challenge: estimating the effect of ketamine on chronic pain and depression in transgender and gender-diverse (TGD) adults using two incompatible published sources: a ketamine cohort with no TGD participants, and an epidemiologic study of TGD adults with no treatment exposure.
 
---
 
## Contributions
 
**Causal Identification**  
Formalizes identification via Pearl's transportability theory, selection diagrams, and S-admissibility, establishing that the ketamine response mechanism is invariant across populations conditional on shared baseline covariates. Derives an explicit transport formula expressing the target interventional distribution as a mixture of source-study response surfaces weighted by the TGD covariate distribution.
 
**Joint Outcome Modeling**  
Motivates joint modeling of pain and depression through a statistical account of both outcomes as coupled Bayesian inference processes, explaining why baseline severity carries substantive predictive weight rather than functioning as a nuisance covariate.
 
**Constrained Prior Predictive Inference**  
Derives an anchor constraint tying the response surface intercept to published source means and characterizes remaining uncertainty via a constrained prior predictive Monte Carlo procedure.
 
**Sensitivity Analysis**  
Conducts sensitivity analyses revealing that the available data cannot support a transport adjustment — the transported estimate is nearly identical to the source mean response across the full range of prior assumptions tested.
 
---


### Data Science Capstone (2025–26)  
**Cloud-Based Baseball Analytics Infrastructure**

Designed end-to-end analytics system for pitch-level tracking data.

- Built Python ETL pipelines to ingest tracking APIs into **PostgreSQL**.
- Developed reproducible **SQL + Python** reporting workflows with CI.
- Automated statistical summaries for pitch- and game-level analysis.
- Prototyping **Streamlit** tools for interactive visualization and model diagnostics.

---

## Past Projects

### Quantitative Analyst Associate — Philadelphia Phillies (Summer 2025)

Independent research on the **Automated Ball-Strike (ABS) Challenge System** at the AAA level.

- Built large-scale **BigQuery SQL + Python** pipelines to compute per-pitch **run expectancy (RE288)** deltas.
- Developed probabilistic **xChallenge models** to predict batter and defense challenge behavior.
- Estimated the **dynamic opportunity cost** of using a challenge and derived per-pitch break-even rules.
- Produced player- and team-level challenge run value leaderboards and decision guidelines.

---

### Biomechanical Drivers of Pitch Velocity (2024)

- Analyzed **Driveline OpenBiomechanics** and **TrackMan** datasets.
- Trained nonlinear models (XGBoost) with group-aware cross-validation, achieving ~2–3 mph prediction error.
- Used feature importance and partial dependence to study energy transfer through the pitching kinetic chain.

---

### Pomona–Pitzer Baseball Analytics (2023–present)  
**Co-Director of Analytics & Data Engineering**

- Developed **Stuff+ / Pitching+ / Location+** models for NCAA Division III evaluation.
- Built opponent scouting pipelines and automated reporting workflows.
- Maintained SQL databases and Python tooling to support in-season decision-making.

---

## Technical Skills

**Programming:** Python, R, SQL, Bash  
**Statistics & ML:** Bayesian inference, causal inference, probabilistic modeling, calibration, simulation studies, group-aware cross-validation  
**Libraries:** XGBoost, scikit-learn, tidymodels, tidyverse, pandas, NumPy, Matplotlib, SHAP  
**Databases & Workflow:** Google BigQuery, PostgreSQL, Git/GitHub, LaTeX

