# Multiple Disease Prediction System with Multiple Algorithms

**Streamlit application for predicting diabetes, heart disease, and Parkinson's disease using pre-trained ML models** :contentReference[oaicite:0]{index=0}

## Table of Contents
- [Features](#features)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Saved Models](#saved-models)
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Tech Stack](#tech-stack)
- [Contributing](#contributing)
- [Contact](#contact)

## Features
- **Disease Predictions:** Predicts diabetes, heart disease, and Parkinson's disease based on clinical and sensor-derived features :contentReference[oaicite:1]{index=1}
- **Interactive UI:** Seamless navigation between disease modules via a Streamlit sidebar menu :contentReference[oaicite:2]{index=2}
- **Real-Time Results:** Instantaneous classification outputs with clear, text-based feedback

## Dataset
All raw CSV datasets are located in the `dataset/` directory and include:
- `diabetes.csv`
- `heart.csv`
- `parkinsons.csv` :contentReference[oaicite:3]{index=3}

## Model Training
End-to-end model training notebooks are provided under `colab_files_to_train_models/`:
- `Multiple disease prediction system - diabetes.ipynb`
- `Multiple disease prediction system - heart.ipynb`
- `Multiple disease prediction system - Parkinsons.ipynb` :contentReference[oaicite:4]{index=4}

## Saved Models
Pre-trained model binaries for immediate inference are stored in `saved_models/`:
- `diabetes_model.sav`
- `heart_disease_model.sav`
- `parkinsons_model.sav` :contentReference[oaicite:5]{index=5}

## Installation
1. **Clone the repository**  
   ```bash
   git clone https://github.com/visezion/Multiple-Disease-Prediction-System-with-Multiple-Algorithm.git
   cd Multiple-Disease-Prediction-System-with-Multiple-Algorithm
