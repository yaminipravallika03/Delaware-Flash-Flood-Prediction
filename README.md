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

Ensure the file paths match your Google Drive structure before running the notebook.

## Methodology

Data Collection: Aggregation of multiple sources including satellite precipitation data, elevation models, and socio-demographic indices.

Preprocessing: Handling missing data, normalizing values, and merging spatial datasets.

Feature Engineering: Creation of relevant flood risk indicators from precipitation, elevation, and land-use features.

Model Selection: Implementing and evaluating decision trees, random forests, and support vector machines.

Hyperparameter Tuning: GridSearchCV applied to optimize the best-performing model.

Evaluation Metrics: Accuracy, Precision, Recall, Confusion Matrix.

## Files in This Repository
- `Delaware Flash Flood.ipynb` - Jupyter Notebook with model training and results.
- `DFF.pptx` - Project slides explaining methodology and findings.

## How to Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yaminipravallika03/Delaware-Flash-Flood-Prediction.git
   ```
2. Mount Google Drive in Google Colab:
``` bash
from google.colab import drive
drive.mount('/content/drive')
```
3. Download the dataset and update file paths to match your Google Drive structure.

4. Run the notebook in Google Colab or Jupyter Notebook.
