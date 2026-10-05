---
layout: single
title: "Code & Reproducibility"
permalink: /software/
author_profile: true
---

I am committed to open science and reproducible research. Below are code repositories I have developed to support pharmacovigilance and drug safety research.

> **Note:** The original pharmacovigilance data used in these projects are owned by regional pharmacovigilance centers (CRPV Bordeaux, CRFV Veneto) and cannot be publicly shared due to regulatory restrictions. The code and methodology are fully provided for reproducibility with similar data structures.

---

## GitHub Repositories

### zGPS-AO-PSI
[github.com/kenenitadesse/zGPS-AO-PSI](https://github.com/kenenitadesse/zGPS-AO-PSI)

Code for ontology-based adverse drug reaction signal detection using zero-inflated Gamma-Poisson Shrinker with post-selection inference.

**Includes:**
- Stratified, random, and thinned data splitting
- Validation-based MSE and ROC metrics
- Permutation testing for multiple comparisons

**Language:** R

---

### Finetuned_MedDRA_Coding
[github.com/kenenitadesse/Finetuned_MedDRA_coding](https://github.com/kenenitadesse/finetuned_meddra_coding)

Code for fine-tuning CamemBERT-bio to verify MedDRA coding in Individual Case Safety Reports.

**Includes:**
- Fine-tuning transformer models for medical text classification
- Binary classification under extreme class imbalance
- Text-only vs. multimodal model comparison

**Language:** Python (PyTorch, Hugging Face Transformers)

---

## Reproducibility Philosophy

I believe in:
- **Open Code:** Making analysis scripts freely available
- **Reproducibility:** Providing complete workflows so others can replicate results
- **Documentation:** Clear instructions for running the code
- **Transparency:** Sharing both successful and failed attempts where relevant

---

## Citation

If you use any of these code repositories in your research, please cite the corresponding publications. For questions or contributions, feel free to open an issue on GitHub or contact me directly.
