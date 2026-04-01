---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on the intersection of **biostatistics**, **pharmacovigilance**, and **data science**, with a particular emphasis on developing advanced statistical methods for monitoring drug safety.

---

## Current Research

### PhD Research: Advanced Statistical Methods and Models for Monitoring Drug Safety
*University of Padova, Italy (2023–Present)*

My doctoral research develops innovative statistical approaches to improve adverse drug reaction detection using real-world data. Key areas include:

- **Zero-Inflated GPS Modeling:** Integrating zero-inflated generalized propensity score modeling with adverse-event ontologies to enhance drug safety signal detection

- **Post-Selection Inference:** Applying post-selection inference techniques to assess model robustness in pharmacovigilance applications

- **NLP for MedDRA Coding from ICSRs:** Fine-tuning transformer-based models to verify MedDRA coding from Individual Case Safety Report narratives

- **NLP for ADR Extraction from Regulatory Labels:** Developing NLP pipelines to automate adverse drug reaction extraction from Summary of Product Characteristics (SmPCs)

---

## Research Projects

### NLP for MedDRA Coding

#### Finetuned MedDRA Coding: NLP-Based Verification of MedDRA Coding
*In collaboration with CRPV Bordeaux-DROM, CHU de Bordeaux*

**Objective:** Determine whether transformer-based NLP models can assess when ICSR narratives contain sufficient clinical information to support GBS-specific MedDRA coding.

**Methods:**
- Fine-tuned CamemBERT-bio on French pharmacovigilance narratives
- Binary classification (narrow vs. broad GBS SMQ terms)
- Evaluation under extreme class imbalance (1% positive cases)

**Results:** Text-only transformer achieved robust performance (F1 = 0.964, AUPRC = 0.980) on balanced subset, demonstrating that narratives contain sufficient clinical signal for coding validation.

**Status:** Manuscript in preparation | GitHub: [Finetuned_MedDRA_coding](https://github.com/kenenitadesse/Finetuned_MedDRA_coding)

---

#### Automated ADR Extraction from Regulatory Drug Labels
*In collaboration with CRFV Veneto, University of Verona*

**Objective:** Automate extraction of adverse drug reactions (ADRs) from Summary of Product Characteristics (SmPCs) to enhance pharmacovigilance efficiency and support drug safety research.

**Methods:**
- NLP extraction using the Polaris system
- Manual annotation by clinical experts as gold standard
- ADR mapping to MedDRA Preferred Terms
- Performance evaluation using recall, precision, F1-score, and accuracy

**Key Consideration:** Following Létinier et al. (2021), accuracy is interpreted alongside other metrics, recognizing its sensitivity to the large number of true negatives in the evaluation framework.

**Status:** Ongoing

---

### Zero-Inflated GPS Modeling & Post-Selection Inference

#### zGPS-AO-PSI: Ontology-Based Mining of Adverse Drug Reactions
*PhD Research*

**Objective:** Develop a novel approach integrating adverse event ontology into a zero-inflated negative binomial model to improve ADR detection in spontaneous reporting systems.

**Methods:**
- Zero-inflated Gamma-Poisson shrinker with AE ontology (zGPS.AO)
- Permutation-based maximum statistic preserving AE correlations
- Data thinning for post-selection inference

**Results:** The ontology-based model consistently outperforms classical GPS, identifying 245 AE signals compared to 15 detected by GPS in real data application.

**Publications:**
- **Dame, K.T.**, Belloni, P., Moretti, U., Scapini, F., Tuccori, M., & Brazzale, A.R. (2025). Exploring ontology-based mining of ADRs. In: di Bella, E., et al. (eds) *Statistics for Innovation IV*. Springer, Cham. [https://doi.org/10.1007/978-3-031-96033-8_63](https://doi.org/10.1007/978-3-031-96033-8_63)
- Dame, K.T., et al. (2025). *Advances in Ontology-Based Mining of Adverse Drug Reactions.* arXiv preprint. [https://arxiv.org/abs/2512.11452v1](https://arxiv.org/abs/2512.11452v1)

**GitHub:** [zGPS-AO-PSI](https://github.com/kenenitadesse/zGPS-AO-PSI)

---

## Grants

### Prevalence and Factors Associated with Diabetes Mellitus
*Jimma University (2021–2022) | Funding: ETB 51,614*

Determined prevalence and factors associated with diabetes mellitus among adults in Southwest Ethiopia using multivariable logistic regression.

### Determinants of Diarrhoea Morbidity among Under-Five Children
*Jimma University (2020) | Funding: ETB 56,262*

Assessed prevalence and factors of diarrheal morbidity using multilevel binary logistic regression analysis.

---

## Methodological Expertise

| **Statistical Methods** | **Pharmacovigilance** | **Machine Learning & NLP** |
|-------------------------|----------------------|----------------------------|
| Survival Analysis | Signal Detection Methods | Predictive Modeling |
| Bayesian Statistics | Disproportionality Analysis | NLP for Biomedical Texts |
| Zero-Inflated Models | Post-Market Surveillance | Transformer Models (CamemBERT-bio) |
| Empirical Bayes Methods | Real-World Evidence | Text Classification |
| Post-Selection Inference | MedDRA Ontology | Fine-Tuning & Transfer Learning |
| Longitudinal Analysis | SmPC & Regulatory Labels | NLP Pipelines (Polaris) |
| Clinical Trials | | |
| Sampling Theory | | |

**Statistical Software:** R, SAS, STATA, SPSS, Python

---

## Open Science

All my research code is available on [GitHub](https://github.com/kenenitadesse). I am committed to reproducible research practices.
