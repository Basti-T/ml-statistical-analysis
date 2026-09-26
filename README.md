# 📊 Statistical Analysis & Data Foundations

> **Core statistical foundations, probability theory, and exploratory data analysis (EDA) implemented in Python for robust machine learning pipelines.**

---

## 🧰 Tech Stack & Tools

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 25px; padding: 20px 0;">
  <a href="https://www.python.org" target="_blank" title="Python"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="55" height="55" /></a>
  <a href="https://pandas.pydata.org/" target="_blank" title="Pandas"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas" width="55" height="55" /></a>
  <a href="https://numpy.org/" target="_blank" title="NumPy"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="NumPy" width="55" height="55" /></a>
  <a href="https://matplotlib.org/" target="_blank" title="Matplotlib"><img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" alt="Matplotlib" width="55" height="55" /></a>
  <a href="https://seaborn.pydata.org/" target="_blank" title="Seaborn"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Seaborn" width="55" height="55" /></a>
  <a href="https://jupyter.org/" target="_blank" title="Jupyter Notebooks"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="Jupyter" width="55" height="55" /></a>
  <a href="https://git-scm.com/" target="_blank" title="Git"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="55" height="55" /></a>
</div>

---

## 🎯 Overview

High-performing machine learning systems and reliable predictive models require rigorous statistical foundations. This repository houses foundational Python implementations and Jupyter Notebooks demonstrating core concepts in statistics, probability, and exploratory data analysis (EDA). 

Rather than abstract theory, these notebooks focus on practical data behavior, underlying distributions, and the mathematical sanity checks necessary before feeding data into enterprise ML architectures.

---

## 📚 Core Topics & Modules

| Module | Focus & Business Relevance | Key Python Libraries |
| :--- | :--- | :--- |
| **Central Tendency** | Measures of central tendency (`Mean-Median-Mode.ipynb`) for baseline profiling. | `Pandas`, `NumPy` |
| **Data Distributions** | Visualizing underlying data spread and skew via histograms (`DataDistributions.ipynb`). | `Matplotlib`, `Seaborn` |
| **Distribution Moments** | Analyzing skewness and kurtosis (`DistributionMoments.ipynb`) to detect anomalies. | `NumPy`, `SciPy` |
| **Dispersion & Variance** | Quantifying data spread (`StandardDevandVar.ipynb`) for risk assessment. | `Pandas`, `NumPy` |
| **Relationship Analysis** | Evaluating variable interactions (`Covariance and Correlation.ipynb`) for feature selection. | `Pandas`, `Seaborn` |
| **Probability Theory** | Conditional probability (`ConditionalProbability.ipynb`) applied to real scenarios. | Python Native |
| **Bayesian Inference** | Updating probabilities with new evidence (`Bayes Theorem.ipynb`) for classification logic. | Python Native |

---

## 📂 Repository Structure

```text
ml-statistical-analysis/
│
├── Bayes Theorem.ipynb             # Bayesian updating & conditional logic
├── Conditional Probability.ipynb   # Event probability scenarios
├── Covariance and Correlation.ipynb# Multi-variable relationship metrics
├── DataDistributions.ipynb         # Distribution shapes & histograms
├── DistributionMoments.ipynb       # Skewness, kurtosis & moment analysis
├── Matplotlib.ipynb                # Custom plotting & visualization guides
├── Mean-Median-Mode.ipynb          # Basic statistical profiling
├── Seaborn Visual.ipynb            # Advanced statistical charting
├── StandardDevandVar.ipynb         # Variance and standard deviation mechanics
├── cars_data.csv                   # Sample dataset for visual exploration
└── normal_distributions_plot.png   # Generated visualization asset
