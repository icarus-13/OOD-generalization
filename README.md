# OOD-generalization

This repository contains codes for my master thesis “Out-of-distribution generalization via invariant prediction: An overview and comparative study”. Codes are presented in Jupyter notebooks and can be run both locally and using third-party vendors like Google Colab. We recommend running the notebooks in Google Colab utilizing GPU for best reproduction.

## Colored MNIST 
The Colored MNIST folder contains three notebooks for the Colored MNIST experiment comparing performance of ERM, IRMv1 and V-REx under concept shift, covariate shift due to digit imbalance and covariate shift due to color imbalance, respectively.

## Synthetic SEM
The Synthetic SEM folder can be used to reproduce results in the Synthetic SEM experiment that compares ERM, IRMv1, V-REx and anchor regression in a regression problem. Users can fine-tune the hyper-parameters manually and each run corresponds to one of the 12 experiment settings presented in the thesis.

--- To switch between heteroskedastic (E) and homoskedastic (O) setting, change the variable setup_hetero.

--- To specify whether training domains are similar (“1”) or far (“0”), change the variable setup_similar.

--- To choose the strength of shift under test domain, manually change the intervention size in the main section at line 95/99 based on which experiment you are running.

## Finance Experiment

The finance experiment folder contains both the notebook and data used for the Finance experiment, where we compare the performance of ERM, IRMv1, V-REx and anchor regression in a semi-classification setting. Data files can be found and downloaded at https://anonymous.4open.science/r/12747e81-8505-43cb-b54e-e75e2344a397/finance_experiments/data. Make sure the notebook is at the same folder directory with the data folder so that the csv files can be properly read.

