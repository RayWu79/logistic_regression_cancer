# Breast Cancer Detection - Logistic Regression

## Project Overview
This project analyzes breast cancer diagnostic data to develop a machine learning model that can accurately classify breast masses as benign or malignant, supporting early detection and improved patient outcomes.

## Analysis Goals
- Develop accurate diagnostic prediction model
- Identify key cellular characteristics for cancer detection
- Evaluate model reliability for clinical support
- Guide diagnostic decision making

## Dataset Description
The Wisconsin Diagnostic Breast Cancer (WDBC) dataset contains:
- ID number - Case identifier
- Diagnosis - Cancer classification (M = malignant, B = benign)
- Cell Nucleus Measurements:
  - Radius - Mean distance from center to perimeter
  - Texture - Standard deviation of gray-scale values
  - Perimeter - Cell boundary length
  - Area - Cell size measurement
  - Smoothness - Local radius variation
  - Compactness - Perimeter² / area - 1.0
  - Concavity - Severity of concave regions
  - Concave points - Number of concave regions
  - Symmetry - Cell shape symmetry
  - Fractal dimension - Cell boundary complexity

## Key Findings

### Model Performance
- Overall Accuracy: 97%
- Benign Detection:
  - Precision: 97%
  - Recall: 99%
  - F1-Score: 98%
- Malignant Detection:
  - Precision: 98%
  - Recall: 95%
  - F1-Score: 96%

### Clinical Implications
1. High Reliability
   - 97% overall accuracy
   - Balanced performance across classifications
   - Robust despite data imbalance

2. Risk Management
   - 95% malignant case detection rate
   - Minimizes dangerous false negatives
   - High precision reduces unnecessary concerns

3. Practical Applications
   - Support for clinical diagnosis
   - Early detection assistance
   - Consistent diagnostic aid

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- NumPy

## Getting Started
1. Clone this repository
2. Make sure you have Anaconda or Miniconda installed
3. Install required environment: `conda env create -f environment.yml`
4. Run the Jupyter notebook: `jupyter notebook`
5. Open `logistic_regression_cancer_notebook`

## Data Source
Wisconsin Diagnostic Breast Cancer (WDBC) dataset from UCI Machine Learning Repository
