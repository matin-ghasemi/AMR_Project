## Mass Spectrometry Dataset for AMR Prediction
This repository contains the code and resources for a project on Antimicrobial Resistance (AMR) Prediction from Mass Spectrometry Data. The raw data used for this project is not included due to its large size and is available for download from the official source.

### 💾 Dataset Information
The project utilizes the DRIAMS (Drug Resistance Infeasible AMR Mass Spectra) public database. This dataset is a comprehensive collection of MALDI-TOF mass spectra profiles from various clinical isolates, linked to their corresponding antimicrobial susceptibility phenotypes. It is an essential resource for training and validating machine learning models for AMR prediction.

The DRIAMS database is composed of multiple sub-collections, with different subsets used for training and validation in this project. Specifically, we used the DRIAMS-A subset for model training and implementation.

### 📥 How to Download the Data
The complete DRIAMS dataset is large and must be downloaded manually from its official host.
* **Original DRIAMS Dataset:**
    * Dryad: https://datadryad.org/dataset/doi:10.5061/dryad.bzkh1899q
* **Preprocessed Dataset (used in this project):**
    * GitHub: https://github.com/xlopez-ml/DL-AMR/tree/master/datasets
    * Kaggle: https://www.kaggle.com/datasets/drscarlat/driams