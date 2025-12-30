# Traffic-Sense

Traffic-Sense is a college team project focused on predicting urban traffic congestion from traffic camera images using an interpretable machine learning pipeline. The system processes images, extracts HOG features, trains classic ML models, and uses a Flask backend for a simple prediction flow.

Right now, this repository contains the available project documentation only. The original dataset and source code are not available here yet.

## What the project does
- Predicts traffic condition from road images captured at multiple locations
- Uses image preprocessing + segmentation + feature extraction
- Trains and compares multiple ML classifiers to select the best performer
- Provides a basic web flow via Flask (planned/used in the project)

## Method overview
1. Image preprocessing: grayscale conversion, Gaussian filtering (noise removal)
2. Segmentation: contour detection to isolate relevant regions
3. Feature extraction: HOG (Histogram of Oriented Gradients) into 1-D NumPy feature vectors
4. Modeling: train and evaluate ML models, then select the best model

## Tech stack used
### Language and environments
- Python 3.11
- Visual Studio Code (VS Code)
- Google Colab

### Backend
- Flask

### Computer vision and ML
- HOG (Histogram of Oriented Gradients) feature extraction
- NumPy arrays for feature storage and processing

### Models trained
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- XGBoost (XGB)

## Documentation
All project documents are inside `docs/`:
- Project report
- Project paper
- Synopsis
- Seminar presentation

## Credits
Developed as a college team project (7th semester).


