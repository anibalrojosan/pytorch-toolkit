# PyTorch Learning Toolkit

This repository contains a collection of Jupyter notebooks documenting my journey learning PyTorch for ML/DL. Each notebook focuses on a specific model, technique, or concept, serving as a hands-on reference.

## Getting Started

To run these notebooks on your local machine, follow these steps. This project uses `uv` for package and environment management.

### 1. Clone the repository
```bash
git clone https://github.com/anibalrojosan/pytorch-toolkit.git
cd pytorch
```

### 2. Create and activate the virtual environment
```bash
# Create the virtual environment
uv venv

# Activate the environment (PowerShell)
.\.venv\Scripts\Activate.ps1

# Or activate the environment (Bash/Zsh)
# source .venv/bin/activate
```

### 3. Install dependencies
With the environment activated, install all the required packages from the `pyproject.toml` file.
```bash
uv sync
```

### (Optional) Register a named Jupyter kernel
If you want to use a named Jupyter kernel, you can register it with the following command.
```bash
uv run python -m ipykernel install --user --name pytorch
```

### 4. Launch Jupyter
You can now launch Jupyter or open the `notebooks/` directory in a compatible IDE like VS Code.
```bash
uv run jupyter notebook
```

---

## Notebooks

Here is a list of the available notebooks and the topics they cover.

| # | Topic | Notebook Path | Description |
|---|---|---|---|
| 01 | **Linear Regression** | [`notebooks/linear_regression/linear_regression.ipynb`](./notebooks/linear_regression/linear_regression.ipynb) | A foundational look at building a simple linear regression model from scratch, covering model definition, training loops, and evaluation. |
| 02 | **Logistic Regression** | [`notebooks/logistic_regression/logistic_regression.ipynb`](./notebooks/logistic_regression/logistic_regression.ipynb) | Classic logistic regression using a single linear layer + sigmoid on linearly separable data, with training, evaluation, and linear decision boundary visualization. |
| 03 | **Neural Network (MLP) for classification** | [`notebooks\neural_networks\nn_for_classification.ipynb`](./notebooks/neural_networks/nn_for_classification.ipynb) | Small Multilayer Perceptron for binary and multiclass classification tasks. |

*More notebooks will be added as I continue learning.*
