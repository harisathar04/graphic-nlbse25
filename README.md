# GRAPHiC Model Selection, Classifier Creation, and Model Loading  

This repository contains the notebooks for training, testing, and using **GRAPHiC**, our submission to the NLBSE'25 tool competition.  

## Notebook Descriptions  

- **`1_GRAPHiC_model_selection.ipynb`**: Covers the selection of the base model for GRAPHiC.  
- **`2_GRAPHiC_creating_classifiers.ipynb`**: Explains how the classifiers were built and trained as part of GRAPHiC.  
- **`3_GRAPHiC_model_loading.ipynb`**: Demonstrates how to load and use the trained GRAPHiC classifiers for inference.  

## Hugging Face Classifiers  

The following classifier, trained as part of GRAPHiC, is uploaded on Hugging Face for easy access:  

1. **Classifier for Java Comments**  
   - Link: [Java Classifier on HF](https://huggingface.co/harisathar04/graphic-nlbse-java)
2. **Classifier for Python Comments**  
   - Link: [Python Classifier on HF](https://huggingface.co/harisathar04/graphic-nlbse-python)
3. **Classifier for Pharo Comments**  
   - Link: [Pharo Classifier on HF](https://huggingface.co/harisathar04/graphic-nlbse-pharo)

## Google Colab  

We provide ready-to-run versions of the notebooks for Google Colab:  

- [`1_GRAPHiC_model_selection.ipynb`](#https://colab.research.google.com/drive/1_IwExSR-YUrMiy-6DDhqbQBZ9Yw5Mt9b)  
- [`2_GRAPHiC_creating_classifiers.ipynb`](#https://colab.research.google.com/drive/1mPsCYRMmG42fhrtORdP6ldL0JrPkFkkZ)  
- [`3_GRAPHiC_model_loading.ipynb`](#https://colab.research.google.com/drive/1hTrl7NtffhMFzTm_OB9fDftQHPvQW7SZ)  

## Contents  

- **Code and Data**  
- **How to Run**  
- **Replicating Results**  
- **Requirements**  

## Code and Data  

- **`1_GRAPHiC_model_selection.ipynb`**: Notebook for model selection.  
- **`2_GRAPHiC_creating_classifiers.ipynb`**: Notebook for creating the classifiers.  
- **`3_GRAPHiC_model_loading.ipynb`**: Notebook for loading and performing inference with the trained classifiers.  
- **`graphic-results.csv`**: A results file containing precision, recall, and F1 scores for each category across Java, Python, and Pharo.  
- **`requirements.txt`**: Contains the dependencies required to run the notebooks.  

## How to Run   

1. Open the Jupyter notebooks:  

   ```bash
   jupyter notebook
   ```  

2. Execute the notebooks in the following order:  

   - Open **`1_GRAPHiC_model_selection.ipynb`** and run all cells to perform model selection.  
   - Open **`2_GRAPHiC_creating_classifiers.ipynb`** and run all cells to create the classifiers.  
   - Open **`3_GRAPHiC_model_loading.ipynb`** and run all cells to load the trained classifiers and perform inference.  

## Replicating Results  

To replicate the results presented in the paper:  

1. Ensure the **`graphic-results.csv`** file is in the same directory as the notebooks.  
2. Follow the steps outlined in each notebook to reproduce the outputs.  
3. The file includes precision, recall, and F1 scores for each category. Compare your outputs with those in **`graphic-results.csv`** for validation.  

## Requirements  

Install the dependencies listed in **`requirements.txt`** before running the notebooks. This ensures all required libraries and packages are available in your environment.  

To install the dependencies:  

```bash
pip install -r requirements.txt
```  

## Support  

If you have questions or encounter any issues, please raise an issue in the repository.  
