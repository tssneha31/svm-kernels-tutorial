# How SVM Kernels Shape Decision Boundaries

This repository contains the code and tutorial for the assignment:

> **How SVM Kernels Shape Decision Boundaries: Linear, Polynomial, and RBF on Toy Datasets**

## Learning objectives

- Explain SVMs intuitively (margin, support vectors, kernel trick).
- Show visually how linear, polynomial, and RBF kernels change the decision boundary on 2D toy datasets.
- Teach how to choose a kernel for different data patterns.
- Implement SVMs with different kernels in Python (scikit-learn) and plot boundaries using accessible colours.

## Repository structure

- `notebooks/svm_kernels_tutorial.ipynb`  
  Main Jupyter notebook that generates all experiments and figures.

- `tutorial/svm_kernels_tutorial.pdf`  
  PDF tutorial submitted for the assignment.

- `figures/`  
  Exported plots used in the tutorial (decision boundaries for each kernel–dataset combination).

- `requirements.txt`  
  Python dependencies needed to run the notebook.

## How to run the notebook

1. Create and activate a virtual environment (optional but recommended).
2. Install dependencies:

   ```bash
   pip install -r requirements.txt

Launch Jupyter and open the notebook:
bash
jupyter notebook notebooks/svm_kernels_tutorial.ipynb
