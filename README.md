# Delaware Flash Flood Prediction

## Overview
This project predicts high-risk flash flood areas in Delaware using machine learning. It integrates FEMA flood maps with socio-demographic data to identify vulnerable communities.

## Data Sources
The dataset includes:
- **Satellite Precipitation Data** (CMORPH Climate Data)
- **Land-Use & Elevation Data** (NOAA & USGS)
- **Socio-Demographic Data** (CDC SVI Index)
- **FEMA Flood Maps** (Public Data)

📌 **Data Access**:  
Since data is stored in Google Drive, download it manually (links are also provided in the notebook).
https://drive.google.com/drive/u/0/folders/1vMnlvdhTzNVR9WItjsn1ldZWnYsL4Aec

## Methodology
- **Feature Engineering**: Data preprocessing and interpolation for flood-risk assessment.
- **Model Used**: Decision Tree Classifier with GridSearchCV for hyperparameter tuning.
- **Evaluation Metrics**: Accuracy, Precision, Recall, Confusion Matrix.

## Files in This Repository
- `Delaware Flash Flood.ipynb` - Jupyter Notebook with model training and results.
- `DFF.pptx` - Project slides explaining methodology and findings.

## How to Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yaminipravallika03/Delaware-Flash-Flood-Prediction.git
   ```
