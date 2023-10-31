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
[Colab]{https://colab.research.google.com/github/nogibjj/Cloud_hosted_notebook_TR/blob/main/main.ipynb}\
### Open the Jupyter Notebook in Colab
1. Search this repo and load the notebook in this repo.
![Screenshot 2023-10-30 at 11 03 55 PM](https://github.com/nogibjj/Cloud_hosted_notebook_TR/assets/104114843/65af3a50-3524-4622-9ea5-f598c7845822)

2. Open and modify the notebook
![Screenshot 2023-10-30 at 11 04 11 PM](https://github.com/nogibjj/Cloud_hosted_notebook_TR/assets/104114843/68a4ea4d-667b-420b-a2a0-47dd784b1690)

3. Connect from colab to github and save the copy
![Screenshot 2023-10-30 at 11 05 23 PM](https://github.com/nogibjj/Cloud_hosted_notebook_TR/assets/104114843/d9a2ab5f-1ff1-4ac1-86a8-1f8c22dcc235)

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
