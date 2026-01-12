# Probabilistic Reasoning Layers for Intraocular Lens Power Prediction: Toward Explainable AI in Ophthalmology

## Overview

This repository hosts a **conceptual prototype** exploring how probabilistic reasoning layers can enhance transparency and uncertainty estimation in **intraocular lens (IOL) power prediction**.
The work combines explainable ML techniques — **SHAP-based feature attribution** and **ensemble variance propagation** — with clinical reasoning principles, aiming to bridge **interpretability** and **reliability** in ophthalmic AI.
It is released as a **research note and proof of concept**, intended to invite discussion and collaborative exploration on how probabilistic interpretability methods might integrate with **real-world medical decision systems**.

---

## Abstract

Modern intraocular lens (IOL) power calculation formulas rely on deterministic regression models that cannot account for patient-level variance or measurement uncertainty.
This work proposes a **probabilistic reasoning layer**, built on SHAP-informed feature weighting and ensemble-based variance propagation, that augments existing prediction models with interpretable confidence estimation.

The framework seeks to improve transparency, mitigate outlier risks, and strengthen human–AI collaboration in ophthalmic decision-making.

---

## Context and Motivation

This conceptual proposal draws inspiration from internal exploratory methods first developed within the **SHAP Lab environment** — a modular framework for explainability and independence testing in machine-learning models.

The same principles of **feature attribution** and **variance analysis** used in SHAP Lab inform the probabilistic reasoning layer proposed here.
Future work will extend these components toward **uncertainty calibration** and **clinician-interpretable visualization** within ophthalmic prediction pipelines.

---

## Methodological Outline

1. **Feature Attribution:**
   SHAP (Shapley Additive Explanations) quantify per-feature contributions to IOL prediction outcomes.

2. **Uncertainty Propagation:**
   A variance-weighted ensemble aggregates predictions from multiple regressors to estimate confidence intervals.

3. **Human-Readable Mapping:**
   Model reasoning is translated into interpretable metrics linking biometric parameters (axial length, keratometry, etc.) to prediction variance.

---

## Repository Contents

- `IOL_reasoning_layer.md` — full paper text (Markdown format)
- `IOL_reasoning_layer.pdf` — formatted PDF version for reference or submission
- `requirements.txt` - dependency list for future prototype implementation (e.g., scikit-learn, shap, pandas)
  
