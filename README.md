# Graph Tsetlin Machine for Image Classification

This repository contains the implementation and experiments for applying the Graph Tsetlin Machine to color image classification tasks on the CIFAR-10 dataset. The project explores how image processing techniques like adaptive Gaussian thresholding and color thermometer encoding influence classification performance.

Developed as part of a course project in computer vision.

## Project Goals

- Implement and experiment with the Graph Tsetlin Machine for color image data.
- Compare the performance of different preprocessing and booleanization methods.
- Reproduce and evaluate experimental results on the CIFAR-10 dataset.


## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ylvagr/ikt452g25v.git

cd ikt452g25v
```

### 2. Create a Virtual Environment (Recommended)

It is recommended to use a Python virtual environment to keep the dependencies isolated:

```bash
# Create a virtual environment
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate
```

### 3. Install Dependencies

After activating the virtual environment, install the required Python packages using the provided 'requirements.txt' file:

```bash
pip install -r requirements.txt
```

You should now be able to run the experiments.

## References

- Graph Tsetlin Machine [Granmo et al., 2025](https://github.com/cair/GraphTsetlinMachine)
- CIFAR-10 Dataset [Krizhevsky, 2009](https://api.semanticscholar.org/CorpusID:18268744)
