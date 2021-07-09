# Prenylation Cleavage Prediction

## Operating System

Ubuntu 18.04.4

## Getting started
Use these commands to download the repository and the necesary inputs datasets.
```
# download this repository
git clone https://github.com/esbgkannan/prenylation_cleavage_prediction
cd prenylation_cleavage_prediction

# download input files
wget https://www.dropbox.com/sh/5jutikv62u9v9ev/AACRyu2MODVU7HFtPd4lQyeea
unzip AACRyu2MODVU7HFtPd4lQyeea
rm AACRyu2MODVU7HFtPd4lQyeea
```

## Python modules
We use the following modules which are not part of the Python 3 standard library.
```
numpy==1.15.4
pandas==0.24.2
scikit-learn==0.21.2
torch==1.7.1+cu101
```

## General overview

### Train & assess prediction models for prenylation
training_prenylation.ipynb

### Train & assess prediction models for cleavage
training_cleavage.ipynb

### Merge predictions to predict the pathway for a given Cxxx sequence
merged_predictions.ipynb

