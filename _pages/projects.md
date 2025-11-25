---
layout: page
title: Data Projects
permalink: /projects/
description: Industry and academic projects in data science, causal inference, and machine learning.
nav: true
nav_order: 2
---

A selection of **data science** and **analytics projects** demonstrating expertise in causal inference, machine learning, and product analytics.

---

## Industry Projects

### 🚀 Financial Super App Integration Analysis
**Viva Republica (Toss)** · Data Product Manager

**Context**: Toss evolved from a simple payment app into Korea's leading financial super-app, integrating banking and securities subsidiaries into the main ecosystem.

**Challenge**: Quantify the *true* causal engagement uplift from financial service integration, separating it from organic growth and seasonal trends.

**My Approach**:
- Designed quasi-experimental framework using cohort-based analysis
- Applied **Difference-in-Differences** methodology with staggered adoption
- Created synthetic control groups from users with different adoption timing
- Built automated reporting pipeline for ongoing measurement

**Impact**: Findings directly informed C-level decisions on product integration strategy and resource allocation across Toss's **20M+ user base**.

**Tech Stack**: `Python` `SQL` `pandas` `statsmodels` `Airflow`

---

### 📊 DiD-Inspired Engagement Metric System
**Viva Republica (Toss)** · Data Product Manager

**Problem**: Traditional engagement metrics fail to capture each service's *causal contribution* to overall app usage—they conflate correlation with causation.

**Innovation**: Developed a **Difference-in-Differences–based engagement metric** that estimates each service's incremental impact on total app usage.

**Methodology**:
- Compare user engagement before/after adopting specific features
- Control for user characteristics and time trends
- Account for selection bias in feature adoption

**Deployment**: The metric system was integrated into Toss's product decision pipeline, enabling PMs to prioritize features based on **true causal impact** rather than simple usage correlations.

**Tech Stack**: `Python` `SQL` `A/B Testing Framework` `Internal BI Tools`

---

## Academic Projects

### 🧠 Deep Learning for Inflation Forecasting
**Course**: Data Science for Economic Analysis · **Grade: A+**

**Objective**: Compare traditional econometric approaches with modern deep learning for macroeconomic forecasting.

**Methods Implemented**:
- Vector Autoregression (VAR) - traditional baseline
- **Bayesian LSTM** - uncertainty quantification
- Transformer architecture - attention mechanisms

**Key Techniques**:
- Time-series cross-validation to prevent data leakage
- Hyperparameter tuning with Bayesian optimization
- Uncertainty quantification via dropout-based approximation

**Findings**: Bayesian LSTM showed improved uncertainty quantification, though VAR remained competitive for short-horizon forecasts. Deep learning excelled at capturing non-linear dynamics.

**Tech Stack**: `PyTorch` `pandas` `statsmodels` `matplotlib`

---

### 🏀 NBA Undervalued Player Analysis
**Course**: Machine Learning Programming · **Grade: A+**

**Objective**: Identify undervalued NBA players using machine learning—a Moneyball approach to basketball.

**Methodology**:
1. **Feature Engineering**: Player statistics, team performance, market data
2. **Model Training**: Decision Tree, Random Forest, Gradient Boosting
3. **Interpretability**: SHAP values for feature importance

**Key Insight**: Defensive metrics and advanced efficiency stats were systematically **underweighted by the market**, creating opportunities to identify value-add players overlooked by traditional scouting.

**Tech Stack**: `scikit-learn` `XGBoost` `SHAP` `pandas`

---

## Technical Skills

### Programming Languages
`Python` `R` `SQL` `Stata`

### Machine Learning & Data Science
`scikit-learn` `PyTorch` `TensorFlow` `XGBoost` `LightGBM`

### Data Analysis
`pandas` `NumPy` `tidyverse` `Matplotlib` `Seaborn` `Plotly`

### Tools & Infrastructure
`Git` `Docker` `AWS` `Airflow` `Jupyter` `Tableau`

---

## What I'm Working On

- 🔬 Applying **causal forest** methods to labor economics questions
- 📊 Building reproducible research pipelines with modern MLOps tools
- 📚 Preparing for Data Science M.S. programs (Fall 2026)

---

*Interested in collaborating or discussing data science projects? [Reach out!](mailto:thomas96124@gmail.com)*

