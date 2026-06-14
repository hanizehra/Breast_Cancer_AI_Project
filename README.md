# Breast Cancer Diagnosis — ML Lab Project

University AI Lab project for breast cancer diagnosis using classical machine learning.

## Description

This project builds a machine learning pipeline to classify breast tumors as **malignant** or **benign** using the Wisconsin Breast Cancer dataset from scikit-learn. All work is done in a single Jupyter notebook with traditional ML models — no deep learning.

## Tech Stack

- **Python** (virtual environment)
- **numpy** — numerical operations
- **pandas** — data handling
- **matplotlib** & **seaborn** — visualization
- **scikit-learn** — dataset, preprocessing, and ML models
- **Jupyter** — notebook environment

## Project Structure

```
Breast_Cancer_AI_project/
├── breast_cancer_project.ipynb   # Main notebook (all project work)
├── .gitignore
├── README.md
└── venv/                         # Local virtual environment (not tracked)
```

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/hanizehra/Breast_Cancer_AI_Project.git
   cd Breast_Cancer_AI_project
   ```

2. Create and activate a virtual environment:
   ```powershell
   python -m venv venv
   .\venv\Scripts\Activate.ps1
   ```

3. Install dependencies:
   ```powershell
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter ipykernel
   ```

4. Register the kernel and open the notebook:
   ```powershell
   python -m ipykernel install --user --name=breast_cancer --display-name="Python (breast_cancer)"
   jupyter notebook breast_cancer_project.ipynb
   ```

## Dataset

Loaded directly from scikit-learn — no external downloads:

```python
from sklearn.datasets import load_breast_cancer
cancer = load_breast_cancer()
```

- **569 samples**, **30 features** (cell nucleus measurements)
- **Target:** 0 = malignant, 1 = benign

## Author

University AI Lab — [Your Name / Student ID]

## License

Academic use only.
