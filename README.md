# PyTorch For Deep Learning

This repository is a beginner-friendly PyTorch learning path built around a sequence of Jupyter notebooks. It starts with tensors and basic operations, moves into neural network training, and finishes with convolutional neural network concepts and a full MNIST CNN example.

The notebooks are designed to be studied in order. Most of them are Colab-ready, and several include an Open in Colab badge so you can run them without setting up a local environment first.

## What This Repo Covers

- PyTorch tensors, tensor operations, and reshaping
- Basic neural network building blocks and forward passes
- A simple training pipeline on the Iris dataset
- CNN concepts such as kernels, pooling, convolutional layers, and RGB images
- A complete CNN example for handwritten digit classification with MNIST

## Notebook Roadmap

| Order | Notebook | Topic |
| --- | --- | --- |
| 1 | [PyTorch_01.ipynb](PyTorch_01.ipynb) | Introduction to PyTorch and the first tensor examples |
| 2 | [PyTorch_02.ipynb](PyTorch_02.ipynb) | Python lists, NumPy arrays, and PyTorch tensors |
| 3 | [PyTorch_03.ipynb](PyTorch_03.ipynb) | Tensor reshaping, views, and slicing |
| 4 | [PyTorch_04.ipynb](PyTorch_04.ipynb) | Tensor math and arithmetic operations |
| 5 | [PyTorch_05.ipynb](PyTorch_05.ipynb) | Building a first neural network module |
| 6 | [PyTorch_06.ipynb](PyTorch_06.ipynb) | Iris dataset training pipeline and model evaluation |
| 7 | [PyTorch_07.ipynb](PyTorch_07.ipynb) | Iris classifier model definition and setup |
| 8 | [PyTorch_08.ipynb](PyTorch_08.ipynb) | Iris classifier model workflow and refinement |
| 9 | [PyTorch_09.ipynb](PyTorch_09.ipynb) | Iris classifier workflow continuation and results |
| 10 | [PyTorch_10.ipynb](PyTorch_10.ipynb) | Image filters and kernels for CNNs |
| 11 | [PyTorch_11.ipynb](PyTorch_11.ipynb) | Pooling layers and downsampling in CNNs |
| 12 | [PyTorch_12.ipynb](PyTorch_12.ipynb) | Convolutional layers and RGB image concepts |
| 13 | [PyTorch_13.ipynb](PyTorch_13.ipynb) | CNN theory recap and review notes |
| 14 | [CNN.ipynb](CNN.ipynb) | End-to-end beginner CNN walkthrough on MNIST |

## Recommended Learning Order

Start with notebooks 1 through 6 to build a strong foundation in tensors and simple supervised learning. Then continue with notebooks 7 through 9 for a fuller Iris classification workflow, and finish with notebooks 10 through 14 to move into CNN concepts and image classification.

## Getting Started

### Option 1: Run in Google Colab

Most notebooks are already prepared for Colab. Open the notebook in GitHub and use the Open in Colab badge at the top of the notebook, or upload the file directly to Colab.

### Option 2: Run Locally

Use a Python 3 environment with Jupyter support, then install the core dependencies:

```bash
pip install torch torchvision numpy pandas matplotlib scikit-learn jupyter
```

If you want GPU acceleration, install the PyTorch build that matches your CUDA setup from the official PyTorch installation instructions.

## Typical Dependencies

- torch
- torchvision
- numpy
- pandas
- matplotlib
- scikit-learn

## Notes

- Several notebooks download datasets at runtime, including Iris and MNIST.
- The notebooks use random seeds such as `torch.manual_seed(42)` in places where reproducibility matters.
- Some notebooks are explanatory and contain mostly markdown, while others are code-heavy and include training or visualization steps.
- This repository does not currently include a pinned requirements file, so dependency versions may vary by environment.

## Contributing

If you extend the notebook series, keep the notebook order and topic progression consistent so new readers can follow the learning path without guessing the prerequisites.
