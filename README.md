# Genetic Feature Selection with Logistic Regression

This repository accompanies the **Modelos Estadísticos Lineales** course and explores a *genetic algorithm (GA)* for feature selection in a bankruptcy‑prediction problem.
The GA’s performance is compared with the two classical wrappers we covered in class—**forward selection** and **backward selection**—using a logistic regression classifier.

---
## Folder Structure

| Path                  | Description                                                                                                                                                                     |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `project/`            | Data files (`Datapooled.csv`) and core Python modules (`GeneticNeuralNetwork.py`, `LocalSearch.py`, etc.) that implement GA, forward, and backward feature‑selection functions. |
| `Resultados Finales/` | Jupyter notebook (`Results-feature-selection.ipynb`) that runs the experiments and tables with the final metrics reported in the paper.                                         |
---

## Quick Start (Google Colab)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HaiderFonseca/logistic-regression-to-predict-bankrupcy/blob/main/project/Results-feature-selection.ipynb)

> **Runtime:** the notebook takes **\~15 minutes** on the free Colab GPU/CPU tier.

---

## What to Expect

| Method                | Precision (Bankrupt) | Recall (Bankrupt) | F1‑score (Bankrupt) |
| --------------------- | -------------------- | ----------------- | ------------------- |
| **Genetic selection** | 0.05                 | **0.80**          | **0.10**            |
| Forward selection     | 0.05                 | 0.78              | 0.10                |
| Backward selection    | 0.05                 | 0.75              | 0.09                |

*Full tables are available in `Resultados Finales/`.*

---

```
Haider Yesid Fonseca Najar, Felipe de Jesús Liévano Pinilla, Iván Andrés Trujillo.
“Genetic feature selection using logistic regression to predict bankruptcy: Colombian case.”
```

