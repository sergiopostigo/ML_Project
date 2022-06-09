# ML_Project

Install dependencies:

If using pipenv:
```shell
pipenv install
```
Otherwise:
```shell
pip install requirements.txt
```
    
Run the jupyter notebooks. They are meant to be run in the following order, since they may have dependencies:  
 - `./scripts/data_analysis.ipynb`  
 - `./scripts/data_cleaning.ipynb`  
 - `./scripts/data_preprocessing.ipynb`  
 - `./scripts/models.ipynb`
    
If running from a cloned repo, make sure the following folders are created before run to avoid any error:
 - `./data`
 - `./data/raw_data`
 - `./data/cleaned_data` 
 - `./data/preprocessed_data` 

