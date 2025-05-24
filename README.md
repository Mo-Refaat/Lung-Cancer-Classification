# Lung Cancer Classification Project

## Overview
This project aims to classify lung cancer risk using machine learning algorithms based on survey data. The dataset contains 309 samples with 16 attributes related to patient demographics, lifestyle, and symptoms. The analysis and modeling are performed in the Jupyter notebook `lung_cancer_classification.ipynb`.

## Dataset
- **Source:** [Kaggle - Lung Cancer Dataset](https://www.kaggle.com/datasets/nancyalaswad90/lung-cancer)
- **File:** `survey lung cancer.csv`
- **Attributes:**
  - Gender: M (male), F (female)
  - Age: Age of the patient
  - Smoking, Yellow fingers, Anxiety, Peer pressure, Chronic Disease, Fatigue, Allergy, Wheezing, Alcohol, Coughing, Shortness of Breath, Swallowing Difficulty, Chest pain: YES=2, NO=1
  - Lung Cancer: YES, NO (target)

## Project Structure
- `lung_cancer_classification.ipynb`: Main notebook with data analysis, visualization, feature selection, and model training.
- `survey lung cancer.csv`: The dataset used for training and evaluation.

## Main Steps
1. **Data Loading & Exploration:**
   - Load the dataset and explore distributions and correlations.
2. **Preprocessing:**
   - Handle categorical variables and scale features.
3. **Feature Selection:**
   - Analyze feature importance and correlations.
4. **Model Training & Evaluation:**
   - Train and evaluate multiple classifiers:
     - Logistic Regression (with GridSearch)
     - Decision Tree (with GridSearch)
     - Random Forest (with GridSearch)
     - Support Vector Machine (SVM, with GridSearch)
     - K-Nearest Neighbors (KNN)
   - Compare accuracy and classification reports.

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn

## Usage
1. Open `lung_cancer_classification.ipynb` in Jupyter Notebook.
2. Run all cells to reproduce the analysis and results.
3. You can modify model parameters or add new models for further experimentation.

## Contact
- **Email**: [Mohamed Refaat](mailto:morefaat356@gmail.com)
