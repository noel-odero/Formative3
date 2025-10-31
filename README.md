# Formative 3 – Probability Distributions, Bayesian Probability, and Gradient Descent

**Group Members:** Angie Noel, Modestine Nformi, Sharif Kiviiri, Josephine Kanu

This repository contains three analytical notebooks that demonstrate probability concepts, Bayesian reasoning on text data, and optimization experiments with gradient descent. Each notebook includes explanations, code, visualizations, and reproducibility notes.


## Table of Contents
1. Part 1: Bivariate Normal Distribution
2. Part 2: Bayesian Probability Analysis
3. Part 3: Manual Gradient Descent Calculations
4. Part 4: Gradient Descent Implementation
5. Conclusions and Insights

---

## Part 1: Bivariate Normal Distribution

### 1.1 Dataset Description
- Source: [[link](https://huggingface.co/datasets/electricsheepafrica/Energy-Indicators-For-African-Countries)]


### 1.2 Implementation
[Import your modular code]
from src.bivariate_normal import calculate_pdf, plot_contour, plot_3d

### 1.3 Mathematical Foundation
[Explain the bivariate normal formula you implemented]

### 1.4 Results
[Display your contour and 3D plots with explanations]

### 1.5 Analysis
[Interpret what the distribution shows]

---

## Part 2: Bayesian Probability Analysis

### 2.1 Keyword Selection
**Positive Keywords:** [list]
**Negative Keywords:** [list]
**Rationale:** [why these keywords]

### 2.2 Chosen Approach
We calculated: P(Positive | keyword)

### 2.3 Results Tables
[Create formatted tables for each keyword]

### 2.4 Implementation
[Show your Bayes' theorem code]

### 2.5 Insights
[Discuss what the posterior probabilities reveal]

---

## Part 3: Manual Gradient Descent Calculations

### 3.1 Problem Setup
[State the given parameters clearly]

### 3.2 Manual Calculations Summary
[Insert images of your handwritten PDF]
- Iteration 1 (Member A): [summary]
- Iteration 2 (Member B): [summary]
- [etc.]

### 3.3 Observed Trends
[Discuss convergence]

---

## Part 4: Gradient Descent Implementation

### 4.1 Code Implementation
We implemented a core function (or class) to execute Batch Gradient Descent for our Linear Regression model ($h_\theta(x) = \theta_0 + \theta_1 x$).
This code manages the iterative process, which includes three main steps in each cycle:
1. Hypothesis Calculation: Generating predictions ($h_\theta(x)$) using the current $\theta_0$ and $\theta_1$ values.
2. Gradient Calculation: Computing the partial derivatives ($\frac{\partial J}{\partial \theta_0}$ and $\frac{\partial J}{\partial \theta_1}$) by calculating the mean of the errors (weighted by $x$ for $\theta_1$).
3. Parameter Update: Simultaneously updating both $\theta_0$ and $\theta_1$ using the formula:

$$\theta_j := \theta_j - \alpha \frac{\partial J}{\partial \theta_j}$$

where $\alpha$ is the defined Learning Rate.

### 4.2 Visualizations
[Two plots: parameters over iterations, error over iterations]
1. Error Over Iterations: This plot shows the value of the Cost Function ($J$) decreasing with each iteration. This confirms that the Gradient Descent algorithm is successfully optimizing the parameters and moving the model toward the local minimum.
2. Parameters Over Iterations: This plot tracks the specific path that the $\theta_0$ and $\theta_1$ parameters take during training, illustrating their gradual convergence to their optimal final values.

### 4.3 Verification
[Compare with manual calculations]
The final optimized parameters obtained from the implemented Gradient Descent code (the converged $\theta_0$ and $\theta_1$ values) were used to calculate the final minimum loss. This result was compared against the manual step-by-step calculations from Part 3 to verify the algorithmic correctness and ensure the implementation successfully minimized the Mean Squared Error (MSE) loss function.
---

## Conclusions
[Overall insights from all parts]

## Individual Contributions
[Brief summary, detailed version in contributions.pdf]

Team Contributions Report

Part 1: Bivariate Normal Distribution
- Member A: [specific tasks]
- Member B: [specific tasks]

Part 2: Bayesian Probability
- Member A: [specific tasks]
- Member B: [specific tasks]

Part 3: Manual Calculations
- Member A: Iteration 1
- Member B: Iteration 2
[etc.]

Part 4: Gradient Descent Code
- Member A: Josephine Duba Kanu Implemented and verified the Batch Gradient Descent algorithm for the Linear Regression model. My tasks included coding the iterative parameter updates, calculating the loss and gradient in each step, and creating the key visualizations showing cost minimization and parameter convergence.