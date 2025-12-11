# Backpropagation_tutorial
Backpropagation tutorial
# Backpropagation Demystified: From Theory to Neural Network Training in Practice

This repository contains the code and report for my tutorial:

> **“What are the roles of forward propagation and backpropagation, and how do they work together to make neural networks learn?”**

The project uses a **synthetic credit-risk dataset** and a small **1-hidden-layer neural network** implemented from scratch in NumPy.  
The main goals are:

- to **illustrate forward propagation** (how a network makes predictions),  
- to **explain backpropagation** (how gradients are computed via the chain rule), and  
- to show experimentally that **forward-only does not learn**, but **forward + backpropagation + gradient descent does**.

---

## 1. Repository contents

Replace the filenames below with your exact ones if needed.

- `backprop_credit_risk_structured_with_markdown.ipynb`  
  Jupyter notebook with:
  - dataset generation (`income()`),
  - forward pass implementation,
  - backpropagation implementation,
  - training loop,
  - experiments (forward-only vs backprop, learning-rate effects),
  - gradient checking for one weight,
  - and plots of loss/accuracy.

- `backprop_tutorial_updated_with_plots_and_code.pdf`  
  Final written tutorial (1500–2000 words) explaining the theory and experiments,  
  with key equations, code snippets and figures.

- `backprop_tutorial_updated_with_plots_and_code.docx`  
  Editable Word version of the tutorial.

- `LICENSE`  
  License file describing how others are allowed to use this work.

*(You may also have extra files like screenshots of plots or intermediate drafts — that’s fine.)*

---

## 2. How to run the notebook

### 2.1. Requirements

You will need:

- Python 3.9+ (or similar)
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `jupyter` or `jupyterlab`

You can install them with:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
