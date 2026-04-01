# Human Activity Recognition (HAR)

Simple Human Activity Recognition project using sensor data to classify physical activities.

## Overview
This project uses time-series data from sensors (e.g., accelerometer, gyroscope) to recognize human activities using machine learning models.

## Features
- Data preprocessing and normalization  
- Sliding window segmentation  
- Baseline model for activity classification  
- Leave-One-Subject-Out (LOSO) validation for robust evaluation  

## Models
- **HAR_Model.ipynb**: Baseline model using standard training/testing  
- **HAR_Model_loso.ipynb**: LOSO-based model for subject-independent evaluation  


## Usage
1. Open the notebook:
   ```bash
   HAR_Model.ipynb  # or HAR_Model_loso.ipynb 
Run all cells to train and evaluate the model.
## Output
- Activity predictions
- Model performance metrics

### Notes
- LOSO validation provides a more realistic evaluation for unseen users
- Baseline model may perform better but is less generalizable