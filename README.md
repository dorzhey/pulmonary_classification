# 🫁 Lung Pathology Prediction from CT Scans 🖼️

This project demonstrates an end-to-end pipeline for predicting lung pathologies such as pulmonary embolism and lung cancer using CT scans. The workflow includes data preprocessing, model training, and inference.

## 📓 Notebook Structure

1. **`explore_and_train.ipynb`**  
    - Importing necessary packages  
    - Handling image size variations  
    - Image preprocessing and testing  
    - Data preparation  
    - Applying SMOTE to balance the dataset

2. **`data_preprocess.ipynb`**  
    - Image normalization and resizing  
    - Data augmentation  
    - Preparing datasets for model training  

3. **`inference.ipynb`**  
    - Running predictions on new CT scan images  
    - Generating model predictions for lung pathology detection  

## ⚙️ Workflow Overview

1. **Data Preprocessing** – Normalizing and preparing CT images.  
2. **Model Training** – Training CNN-based models for pathology classification.  
3. **Inference** – Predicting pathology presence from unseen scans.  

## 🔍 How to Run

1. Run `data_preprocess.ipynb` to prepare the dataset.  
2. Open `explore_and_train.ipynb` to train the model.  
3. Use `inference.ipynb` to predict lung pathologies in new images.  

## 📊 Applications

The pipeline provides insights into lung pathology predictions, which can support medical research and educational applications.

## ⚠️ Disclaimer

This model is for research purposes only and is not intended for clinical diagnosis.
