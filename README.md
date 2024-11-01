# Parameter Optimization of SVM

## Project Overview

This project involves optimizing a Support Vector Machine (SVM) model on a multi-class dataset from the UCI Library, focusing on achieving the best accuracy by fine-tuning parameters. The dataset was split into 70% for training and 30% for testing across 10 different samples. For each sample, SVM was optimized over 100 iterations to determine the best parameters.

## Objectives

1. **Dataset**: Use a multi-class dataset with 5k-30k rows from the UCI library.
2. **Training-Testing Split**: Divide dataset into 70% training and 30% testing.
3. **Optimization**: Optimize SVM for each sample with 100 iterations.
4. **Results Table**: Record best accuracy and parameters (Kernel, Nu, Epsilon) for each sample.
5. **Convergence Graph**: Plot accuracy vs. iterations for the sample with the highest accuracy.

## Results

| Sample # | Best Accuracy | Best SVM Parameters (Kernel, Nu, Epsilon) |
|----------|---------------|-------------------------------------------|
| S1       |               |                                           |
| S2       |               |                                           |
| S3       |               |                                           |
| S4       |               |                                           |
| S5       |               |                                           |
| S6       |               |                                           |
| S7       |               |                                           |
| S8       |               |                                           |
| S9       |               |                                           |
| S10      |               |                                           |

*Complete results can be found in the `results/` directory.*

## Convergence Graph

Below is the convergence graph showing accuracy over iterations for the sample with the highest accuracy:

*(Insert convergence graph image here)*

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sidharthd7/Parameter-Optimization-SVM.git
   cd parameter-optimization-svm
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the optimization script for all samples:
   ```bash
   python optimize_svm.py
   ```
2. View results in the `results/` directory.
