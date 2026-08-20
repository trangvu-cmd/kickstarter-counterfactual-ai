# From Text to Funding: NLP, Explainable Machine Learning and Counterfactual AI for Kickstarter Campaigns

## Overview

This repository contains the code and analytical workflow for my MSc Data Science dissertation at the University of Sheffield.

The project investigates whether the language used in crowdfunding campaigns is associated with funding outcomes, whether linguistic information improves predictive performance beyond campaign metadata, and whether explainable AI can generate actionable recommendations for campaigns predicted to fail.

The study focuses on completed UK Kickstarter campaigns launched in 2025 and combines:

- Data engineering and quality validation
- Natural Language Processing (NLP)
- Statistical analysis
- Explainable machine learning
- Counterfactual explanations
- Large Language Model (LLM) assisted text revision
- Semantic and factual validation

> **Project status:** Dissertation in progress.  
> The repository is being updated alongside the final dissertation and may therefore change as documentation, notebooks and reproducibility materials are completed.

---

## Research Aim

The project aims to investigate the role of campaign language in UK reward-based crowdfunding and evaluate whether explainable, model-based linguistic recommendations can be translated into meaningful and factually consistent campaign revisions.

---

## Research Questions

### RQ1
Which linguistic characteristics of Kickstarter campaign headlines and blurbs are associated with successful and unsuccessful funding outcomes after relevant campaign characteristics are taken into account?

### RQ2
To what extent do linguistic features derived from campaign headlines and blurbs improve the prediction of UK Kickstarter campaign outcomes beyond campaign metadata alone, and which characteristics are most influential in the resulting predictions?

### RQ3
For campaigns predicted to fail, what minimal changes to actionable linguistic characteristics are required to change the model's prediction, and to what extent can an LLM implement these changes while preserving the original meaning and factual information?

---

## Analytical Framework

The project follows an end-to-end analytical pipeline:

```text
Kickstarter data
       ↓
Data cleaning and validation
       ↓
UK / GBP / completed 2025 campaigns
       ↓
Headline and blurb processing
       ↓
Linguistic feature engineering
       ↓
Statistical association analysis
       ↓
Predictive machine learning
       ↓
Explainable model interpretation
       ↓
Counterfactual optimisation
       ↓
LLM-assisted campaign revision
       ↓
Re-extraction and model re-scoring
       ↓
Semantic and factual validation
