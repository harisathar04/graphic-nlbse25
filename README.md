# GRAPHiC Model Selection and Classifier Creation

This repository contains our notebooks for training, testing, and using GRAPHiC, our submission to the NLBSE'25 tool competition.

## Notebook Descriptions

1. **1_GRAPHiC_model_selection_(NLBSE'25).ipynb**: Outlines how we selected the base model and tuned the hyperparameters.
2. **2_GRAPHiC_creating_classifiers_(NLBSE'25).ipynb**: Shows how we created the classifiers that make up GRAPHiC.

## Google Colab

If you wish to run the notebooks in Google Colab, we provide the following ready-to-go notebooks:

1. **1_GRAPHiC_model_selection**
2. **2_GRAPHiC_creating_classifiers.ipynb**

## Contents

1. [Code and Data](#code-and-data)
2. [How to Run](#how-to-run)
3. [Replicating Results](#replicating-results)

## Code and Data

- **1_GRAPHiC_model_selection_(NLBSE'25).ipynb**: Notebook for performing model selection.
- **2_GRAPHiC_creating_classifiers_(NLBSE'25).ipynb**: Notebook for creating classifiers.
- **graphic-results.csv**: A sample results file used for benchmarking or comparison.

## How to Run

1. Open the Jupyter notebooks:

   ```bash
   jupyter notebook
   ```

2. Run the cells in the following order:
   - Open **1_GRAPHiC_model_selection_(NLBSE'25).ipynb** and execute all cells to perform model selection.
   - Open **2_GRAPHiC_creating_classifiers_(NLBSE'25).ipynb** and execute all cells to create classifiers.

## Replicating Results

To replicate the results presented in the paper:

1. Ensure the **graphic-results.csv** file is in the same directory as the notebooks.
2. Follow the steps outlined in the notebooks to generate the expected outputs.
3. Compare your outputs with those in the `graphic-results.csv` file.

For further questions or issues, please raise an issue in the repository.
