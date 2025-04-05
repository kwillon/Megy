# MEGY: Prediction of Magnetic Properties of Nanoparticles

## Overview
MEGY is a machine learning project aimed at predicting key magnetic properties of nanoparticles, specifically:
- **Coercivity**
- **Remanence magnetization**
- **Saturation magnetization**

This project is a part of a larger initiative, AI Lab Assistant, designed to assist with the prediction and optimization of nanoparticle synthesis. The project leverages a variety of descriptors for nanoparticles and includes models for both coated and uncoated nanoparticles.

<div align='middle'><img src='data/pic1.jpg' style='width: 80%; min-width: 200px;'/></div>

## Contents

### `models/`
Contains Jupyter notebooks (`.ipynb` files) with the following:
- **Models**: Trained machine learning models for predicting the magnetic properties.
- **Visualizations**: Scatter plots and feature analysis plots using SHAP (Shapley Additive Explanations) for interpreting the model’s predictions.

### `data/`
Includes the datasets used for training the models. These datasets contain information about nanoparticle properties and their corresponding magnetic characteristics.

## Installation

To get started with MEGY, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/MEGY.git
cd MEGY
pip install -r requirements.txt