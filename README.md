# ML Fundamentals

ML projects with Jupyter notebooks. Linear regression, housing price prediction, logistic regression, and CNN image classification.


## Projects

### Linear Regression
- `linear-regression/linear-regression.ipynb` - Linear regression fundamentals
- `linear-regression/bikers_data.csv` - Bikers dataset

### Housing Price Regression
- `housing-price-regression/housing-price-regression.ipynb` - Predict house prices
- `housing-price-regression/house_prices.txt` - Housing dataset

### Logistic Regression
- `logistic-regression/logistic-regression.ipynb` - Classification on spiral data
- `logistic-regression/spiral_features.npy` - Feature data
- `logistic-regression/spiral_target.npy` - Target labels

### CIFAR-10 Image Classification
- `cifar10-image-classification/cifar10_cnn.ipynb` - CNN image classification on CIFAR-10 (60k 32x32 images, 10 classes)

### CUDA Check
- `cuda-check/cuda-environment-check.ipynb` - Verify GPU setup

---

## Setup

This repo uses a [Dev Container](https://containers.dev/) with CUDA support. No local Python installation needed.

**Requirements:** Docker Desktop + VS Code with the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).

1. Open the repo in VS Code
2. When prompted, click **Reopen in Container** (or run `Dev Containers: Reopen in Container` from the command palette)
3. VS Code will build the container and install all dependencies automatically

Notebooks run directly in VS Code via the Jupyter extension — no browser needed.

---

Each notebook is self-contained and can be run independently.
