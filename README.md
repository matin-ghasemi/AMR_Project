## Antimicrobial Resistance Prediction from Mass Spectrometry Data

This repository contains the source code and notebooks for a project on predicting antimicrobial resistance (AMR) from MALDI-TOF mass spectrometry data. This work was developed as a part of the **Drug Design** course at **Amirkabir University of Technology**, under the supervision of **Dr. Zahra Ghorbanali**.

### 🧠 Project Overview

The global rise of antimicrobial resistance (AMR) is a major public health concern. This project aims to develop and evaluate machine learning models to predict the resistance profile of the bacterium Staphylococcus aureus to several key antibiotics. We utilize MALDI-TOF mass spectrometry data, which provides a unique "fingerprint" of the bacterial proteome. The core of this research is a multi-label classification approach, where a single bacterial sample can exhibit resistance to multiple antibiotics simultaneously.

### ✨ Key Features and Methodology
+ Data Source: Utilizes the publicly available DRIAMS database of raw mass spectrometry spectra.

+ Model Baseline: Establishes a performance baseline using a range of classical machine learning models, including Random Forest, LightGBM, and Support Vector Machines (SVM).

+ Deep Learning Models: Implements and evaluates two deep learning architectures:

    - A 1D Convolutional Neural Network (CNN) for direct analysis of raw spectra.

    - A 2D CNN that processes mass spectra after a helix matrix transformation, converting 1D data into a 2D image-like format.

+ Multi-label Classification: Formulates the problem as a multi-label task to capture the synergistic relationships between different antibiotic resistance profiles.

### 📁 Project Structure
├── data/ <br>
│   └── README.md 
├── notebooks/<br>
│   ├── 01_EDA.ipynb  <br>
│   ├── 02_Classic_ML.ipynb<br>
│   ├── 03_1D_CNN.ipynb<br>
│   └── 04_Helix_2D_CNN.ipynb <br>
├── .gitignore    <br>
├── requirements.txt       <br>
└── README.md <br>