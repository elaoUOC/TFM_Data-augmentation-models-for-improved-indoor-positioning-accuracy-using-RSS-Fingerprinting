# TFM: Data Augmentation Models for Improved Indoor Positioning Accuracy Using RSS Fingerprinting

This repository contains the implementation of data augmentation techniques developed for the thesis **"Data Augmentation Models for Improved Indoor Positioning Accuracy Using RSS Fingerprinting"**. The project focuses on reducing the time and resources required for creating offline databases in indoor positioning systems based on RSS fingerprinting. 

This project was developed by Esperanza María Laó Amores as part of the Master's Thesis for the **Master's Degree in Data Science** at [Universitat Oberta de Catalunya (UOC)](https://www.uoc.edu). The implementation, analysis, and results are the author's original work.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [File Structure](#file-structure)
6. [Results](#results)
7. [License](#license)
8. [Acknowledgements](#acknowledgements)

---

## Introduction
This project explores the implementation of two data augmentation techniques designed to optimize the offline database creation process for indoor localization systems. The techniques are implemented in a generalizable manner, allowing them to be applied to various datasets. The methodology has been validated using two distinct datasets to evaluate the effectiveness and adaptability of the proposed models.

---

## Features
- Implementation of two data augmentation techniques:
  - Linear Interpolation
  - Generative Adversarial Networks (GANs)
- Compatible with multiple datasets.
- Optimized for Kaggle's computational environment (CPUs/GPUs).
- Fully reproducible results through fixed random seed configurations.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/elaoUOC/TFM_Data-augmentation-models-for-improved-indoor-positioning-accuracy-using-RSS-Fingerprinting.git
   cd TFM_Data-augmentation-models-for-improved-indoor-positioning-accuracy-using-RSS-Fingerprinting

---

## Usage
1. Open the Jupyter Notebooks in the repository for:
    - Data preprocessing.
    - Data augmentation training and evaluation.
3. Adjust the configuration parameters in the notebook to use your dataset.

---

## File Structure
- Notebooks/: Contains Jupyter Notebooks for data preprocessing, augmentation, and evaluation.
- Data/: Example datasets used.
- Output/: Visualizations of experiments.

---

## Results
The implemented techniques demonstrated significant reductions in time and resources required for database creation.
Results highlight the generalizability of the techniques across datasets, achieving consistent improvements in positioning accuracy.

![Results Plot](Output/Comparison%20with%20and%20without%20Data%20Augmentation.png)


---

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

## Acknowledgements
This repository was developed as part of the Master's Thesis for the **Master's Degree in Data Science** at [Universitat Oberta de Catalunya (UOC)](https://www.uoc.edu). I would like to express my gratitude to my thesis supervisor, for their guidance, support, and feedback throughout the project. 

Special thanks to the Kaggle platform for providing computational resources.
