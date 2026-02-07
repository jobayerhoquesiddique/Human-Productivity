# Human-Productivity

A final-year research project on forecasting human productivity state (Burnout vs Flow) using multimodal behavioral and biological signals with a distributed multimodal learning framework.

## Overview
This repository consolidates the full research lifecycle for the project: literature review, methodology, datasets, model artifacts, evaluation results, and figures. The directory is organized to support academic writing and reproducibility, with indexed assets and a standardized file naming convention.

## Research Objective
Build and evaluate a multimodal framework that integrates behavioral and biological indicators to predict productivity state, enabling early risk detection and insight into cognitive load and resilience.

## Key Components
- Multimodal data sources: survey responses, secondary datasets, and biosignal-derived indicators.
- Feature engineering across behavioral, semantic, and biological dimensions.
- Model training and evaluation with baseline comparisons and interpretability analysis.

## Project Structure (Google Drive Standard)
| Folder | Purpose |
| --- | --- |
| `00 Admin` | Admin docs and structure guide |
| `01 Project Overview/Proposal` | Proposal and hypothesis materials |
| `01 Project Overview/Background` | Background and theoretical foundations |
| `02 Literature Review` | Literature reviews and curated registries |
| `03 Methodology` | Research methodology and approach |
| `04 Data` | Datasets, registries, survey responses |
| `05 Models` | Framework and model specifications |
| `06 Results` | Outcomes, evaluation summaries |
| `07 Figures` | Labeled figures and diagrams |
| `08 Notebooks` | Jupyter notebooks |
| `09 Writing` | Paper outline, draft assets |
| `10 Index & Catalogs` | Asset catalog and filename map |
| `99 Archive` | Duplicates and deprecated files |

## Figures and Visuals
**System Architecture**

![Distributed Multimodal Framework](07%20Figures/fig-20_distributed-multimodal-framework_diagram_v01.png)

**Affective Computing Framework**

![Affective Computing Framework](07%20Figures/fig-21_distributed-multimodal-framework_affective-computing_v01.png)

**Evaluation Highlights**

![Final Model ROC Curve](07%20Figures/fig-17_final-model-roc-curve_2026-02-03.png)

**Interpretability**

![SHAP Top Predictors](07%20Figures/fig-18_shap-top-predictors_2026-02-03.png)


## Code and Notebook Snapshots
These screenshots capture key stages from the analysis notebooks.

![Schema Validation](07%20Figures/fig-01_survey-schema-validation_2026-02-03.png)

![Column Heuristics](07%20Figures/fig-03_heuristic-column-matching_2026-02-03.png)

![Class Weights](07%20Figures/fig-04_class-weights-cost-matrix_2026-02-03.png)

![Model Comparison](07%20Figures/fig-16_model-comparison-leaderboard_2026-02-03.png)

## Reproducibility
- Notebooks are located in `08 Notebooks`.
- Figures and plots used in the paper are in `07 Figures` with indexed captions in `10 Index & Catalogs/figure-index.csv`.
- Full asset inventory is available in `10 Index & Catalogs/asset-catalog.csv`.

## Writing Support
A full academic writing workspace is included in `09 Writing`, with an IMRaD outline and a `references.bib` template for citations.

## Citation
If you use this repository for academic purposes, cite the project as:

```
Human-Productivity (CSE 499 FYDP Phase-II). Department of CSE, 2026.
```

## Contact
Jobayer Hoque Siddique
