# Thioetherification-modeling

This is the thioetherification modeling repository, including data related to our project. This repository contains Cartesian coordinates of optimized structures for both electrophiles and nucleophiles. Additionally, you'll find an Excel file that consolidates both experimental and computational data, along with Jupyter notebooks used for data preprocessing and decision tree modeling throughout the project.

For further details, please refer to our associated manuscript available on [ChemRxiv].

[ChemRxiv]: https://chemrxiv.org/engage/chemrxiv/article-details/6499d2fd6e1c4c986b615276

## Contents
- ```electrophiles```/```nucleophiles``` folder: these folders include .xyz files with optimized structures for electrophiles/nucleophiles employed in the data science part of this project. The optimization was conducted with Gaussian16.
- ```notebook``` folder: This folder includes the following Excel sheets and Jupyter notebooks:
  1) ```raw_dataset.xlsx```: Excel file containing experimental reaction results and computational properties for electrophiles and nucleophiles.
  2) ```dataset.xlsx```: Excel file containing the training/test dataset and validation dataset in a comprehensive form with already preprocessed reaction data.
  3) ```01_data_preprocessing.ipynb```: Notebook for feature preprocessing.
  4) ```02_decision_tree_modeling.ipynb```: Comprehensive notebook for training and validating the decision tree model.
