# OOD-generalization

This repository contains codes for my master thesis “Out-of-distribution generalization via invariant prediction: An overview and comparative study”. Codes are presented in Jupyter notebooks and can be run both locally and using thrid-party vendors like Google Colab. We recommend running the notebooks in Google Colab ultilizing GPU for best reproduction.

--- The Colored MNIST folder contains three notebooks for the Colored MNIST experiment comparing performanec of ERM, IRMv1 and V-REx under concept shift, covaraite shift due to digit imbalance and covaraite shift due to color imbalance, respectively.
--- The Synthetic SEM folder can be used to reproduce results in the Synthetic SEM experiment that compares ERM, IRMv1, V-REx and anchor regression in a regression problem. Users can fine-tune the hyper-parameters manually and each run corresponds to one of the 12 experiment settings presented in the thesis.
--- The finance experiment folder contains both the notebook and data used for the Finance experiment, where we compare the performance of ERM, IRMv1, V-REx and anchor regression in a semi-classification setting.
