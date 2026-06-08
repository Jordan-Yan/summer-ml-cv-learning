# Week 0: Environment Setup

## Goal

The goal of this week is to set up my machine learning and computer vision learning environment.

## What I Set Up

* Python virtual environment
* Jupyter Notebook
* numpy
* pandas
* matplotlib
* scikit-learn
* PyTorch
* torchvision
* GitHub repository structure

## Environment Check

I created a notebook named:

`notebooks/00_environment_check.ipynb`

It checks whether the main packages can be imported successfully.

The following packages were successfully imported:

* numpy
* pandas
* matplotlib
* scikit-learn
* torch
* torchvision

## Problems I Met

1. My system Python version is Python 3.14.0, and there was no separate `python3.12` or `python3.11` command.
2. Jupyter showed a SOCKS proxy warning about the missing `socksio` package, but the notebook server still started successfully.
3. When writing `README.md`, I accidentally stayed in heredoc mode because the ending `EOF` was missing.

## What I Learned

1. A machine learning project should have a clear folder structure.
2. A virtual environment keeps project packages separate from the system Python environment.
3. `requirements.txt` records the packages used in the project.
4. Before learning models, I need to make sure the coding environment is stable.
5. Jupyter Notebook must be tested separately, because Terminal import success does not always mean notebook import success.

## Next Step

Next week, I will start my first sklearn classification task using a simple dataset such as Iris or sklearn digits.
