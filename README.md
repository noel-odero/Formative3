# Formative 3 – Probability Distributions, Bayesian Probability, and Gradient Descent

**Group Members:** Angie Noel, Modestine Nformi, Sharif Kiviiri, Josephine Kanu

This repository contains three analytical notebooks that demonstrate probability concepts, Bayesian reasoning on text data, and optimization experiments with gradient descent. Each notebook includes explanations, code, visualizations, and reproducibility notes.

## Notebooks
- [Part1_Bivariate_Normal_Distribution_African_Energy.ipynb](Part1_Bivariate_Normal_Distribution_African_Energy.ipynb) — Exploratory analysis and visualization of a bivariate normal distribution applied to an African energy dataset (correlation, contours, sampling).
- [Part2_Bayesian_Probability.ipynb](Part2_Bayesian_Probability.ipynb) — Implementation of Bayes' Theorem for sentiment keyword analysis on the IMDB dataset. Key functions and symbols:
  - [`calculate_bayes_probabilities`](Part2_Bayesian_Probability.ipynb)
  - [`contains_keyword`](Part2_Bayesian_Probability.ipynb)
  - main DataFrame: [`df`](Part2_Bayesian_Probability.ipynb)
- [Part4_Gradient_Descent.ipynb](Part4_Gradient_Descent.ipynb) — Experiments with gradient descent: learning rates, convergence diagnostics, loss surfaces and plots.

## Core idea (Bayes)
Use Bayes' theorem to compute the probability of a sentiment given a keyword:
$$
P(\text{Positive} \mid \text{keyword}) = \frac{P(\text{keyword} \mid \text{Positive}) \, P(\text{Positive})}{P(\text{keyword})}
$$

## How to run
1. Install dependencies (used across notebooks):
```sh
pip install pandas numpy matplotlib seaborn
```
2. Open the notebooks in VS Code or Colab. Each notebook contains an initial cell with imports and a note on required files.
3. For [Part2_Bayesian_Probability.ipynb](Part2_Bayesian_Probability.ipynb): ensure the IMDB dataset file referenced by the notebook (e.g., "IMDB Dataset.csv") is placed in the same folder or update the path in the notebook.

## Data
- IMDB reviews dataset referenced in [Part2_Bayesian_Probability.ipynb](Part2_Bayesian_Probability.ipynb). Place the CSV in the repository root or update the path in the notebook.

## Project structure
- [Part1_Bivariate_Normal_Distribution_African_Energy.ipynb](Part1_Bivariate_Normal_Distribution_African_Energy.ipynb)
- [Part2_Bayesian_Probability.ipynb](Part2_Bayesian_Probability.ipynb)
- [Part4_Gradient_Descent.ipynb](Part4_Gradient_Descent.ipynb)
- [README.md](README.md)




