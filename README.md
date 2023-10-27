# Week 9: Cloud-Hosted Notebook Data Manipulation
Tianji Rao


[![Install](https://github.com/nogibjj/Cloud_hosted_notebook_TR/actions/workflows/install.yml/badge.svg)](https://github.com/nogibjj/Cloud_hosted_notebook_TR/actions/workflows/install.yml)
[![Format](https://github.com/nogibjj/Cloud_hosted_notebook_TR/actions/workflows/format.yml/badge.svg)](https://github.com/nogibjj/Cloud_hosted_notebook_TR/actions/workflows/format.yml)
[![Lint](https://github.com/nogibjj/Cloud_hosted_notebook_TR/actions/workflows/lint.yml/badge.svg)](https://github.com/nogibjj/Cloud_hosted_notebook_TR/actions/workflows/lint.yml)
[![Test](https://github.com/nogibjj/Cloud_hosted_notebook_TR/actions/workflows/test.yml/badge.svg)](https://github.com/nogibjj/Cloud_hosted_notebook_TR/actions/workflows/test.yml)

## Overview
This repo contains:   
- .devcontainer     
- .github   
- .gitignore    
- Makefile  
- README.md     
- requirements.txt   
- `lib.py`    
- `test_lib.py`      
- `main.py`   
- `test_main.py`  
- Eletric_Vechile_Population_Data.csv  (Dataset)    
- some `.sh` files
- `main.ipynb`


## Purpose
The purpose of this project is applying Cloud-Hosted Notebook Data Manipulation. Here we have one Jupyter notebook, called "main.ipynb", and we can run it on the Google Colab.


## Google Colab
![Colab]{https://colab.research.google.com/github/nogibjj/Cloud_hosted_notebook_TR/blob/main/main.ipynb}

## Dataset
The experimental dataset is Eletric Vehicle Population Data that provided by DATA.GOV. Here I downloaded the .csv file and made it the dataset for testing. The url address is https://catalog.data.gov/dataset/electric-vehicle-population-data. I used `pd.read_csv()` to read this dataset and save as a `pd.DataFrame`.

### Testing Jupyter Notebook
Here we use pytest-nvbal for testing the jupyter notebook outputs.

## Preparation
1. Setting up Codespaces
2. Click the Google Colab link to review the jupyter notebook online

## Check format and test errors
1. Format `make format`
2. Lint `make lint`     

## Reference
https://pandas.pydata.org/    
https://catalog.data.gov/dataset/electric-vehicle-population-data
https://colab.google/
