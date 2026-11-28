# Lab 4: Bayesian Networks

A small Bayesian network (rain → maintenance → train → appointment) built with **pgmpy**:

- defines the graph and its conditional probability tables,
- computes joint probabilities with the chain rule,
- answers questions such as *P(rain | missed appointment)* with **variable elimination**.

| File | Description |
|---|---|
| `bn_lab (1).ipynb` | Lab notebook |
| `lab4 AI (3).pdf` | Lab report with the steps and outputs |

## How to run

Open the notebook in Jupyter or Google Colab and run the cells in order
(the first cell installs `pgmpy`).
