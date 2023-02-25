# SARAlerts
[![DOI](https://zenodo.org/badge/576043558.svg)](https://zenodo.org/badge/latestdoi/576043558)
<img src="emoji.png" alt="drawing" width="200"/>

SARAlerts is a code to generate structural alerts (toxic alerts) using Local Interpretable Model-Agnostic Explanations (LIME) of machine learning models from Tox21, Clintox, and Sider datasets.
SARAlerts means Serious Adverse Reaction Alerts

The SARAlerts framework is highly versatile (coded in Google Colab), with options that can be further developed and optimized by the users: it can accept any user-defined datasets (or datasets available in MoleculeNet repository), can use different fingerprints, data splitters, cross-validation methods, and any classification model from DeepChem library.

There are two complementary codes to analyze the data generated from SARAlerts: Toxic_alert_list_???.ipynb and Molecular_filtering.ipynb

The Clintox and Sider datasets are provided in two xlsx files: clintox.xlsx and sider.xlsx
The Tox21 dataset is upload using DeepChem tools. DeepChem tools may also be used to upload any dataset in MoleculeNet or user-defined dataset. 
<img src="Graphic Abstract.jpg" alt="drawing" width="800"/>
# Installation instructions

SARAlerts is 100% compatible with Google Colab platform developed in Microsoft Windows using Python version 3.8.

SARAlerts has the following dependencies: Lime, RDkit, DeepChem, Pandas, Matplotlib, Statistics, xlsxwriter, and dataframe-image.

# Documentation

The complete documentation about how to run the SARAlerts protocol and several tutorials is being developed.

# Get help

SARAlerts is being actively developed and some issues may arise or you may need extra help to run SARAlerts. In those cases, there are two main ways to get help:

1) Open a new issue in this repository
Or 
2) write an email to André Silva Pimentel (a_pimentel@puc-rio.br) (I will do my best to answer your questions as soon as possible).

# License

SARAlerts is available under MIT License. See license document for more details. URL and DOI: https://github.com/andresilvapimentel/SARAlerts (https://doi.org/10.5281/zenodo.7416484)

# Contributors

This code was written under collaboration:
Cayque Monteiro Castro Nascimento (PhD student), who performed the analysis and Paloma Guimarães Moura (Undergraduate student), who wrote most of the code under my guiding as advisor.
