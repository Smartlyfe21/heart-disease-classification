# Heart Disease Classification

## Overview

This project explores and analyzes a heart disease dataset to build predictive models using machine learning techniques. The goal is to develop models capable of predicting whether or not a patient has heart disease based on clinical parameters. The project includes data preprocessing, model training, cross-validation, and evaluation using key performance metrics such as accuracy, precision, recall, and F1-score.

## Table of Contents
- [Problem Definition](#problem-definition)
- [Data](#data)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Problem Definition

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## Data

The dataset used in this project is the Cleveland Heart Disease dataset from the UCI Machine Learning Repository:
[UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)

A version of this dataset is also available on Kaggle:
[Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)

## Features

This dataset contains various clinical features that are used to predict heart disease. Below is a brief description of each feature:

- `age` - Age in years
- `sex` - (1 = male; 0 = female)
- `cp` - Chest pain type:
  - 0: Typical angina (chest pain due to decreased blood supply to the heart)
  - 1: Atypical angina (chest pain not related to the heart)
  - 2: Non-anginal pain (e.g., esophageal spasms)
  - 3: Asymptomatic (no chest pain)
- `trestbps` - Resting blood pressure (in mm Hg)
- `chol` - Serum cholesterol in mg/dl
- `fbs` - Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg` - Resting electrocardiographic results:
  - 0: Normal
  - 1: ST-T wave abnormality
  - 2: Left ventricular hypertrophy
- `thalach` - Maximum heart rate achieved
- `exang` - Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak` - ST depression induced by exercise relative to rest
- `slope` - Slope of the peak exercise ST segment:
  - 0: Upsloping (better heart rate with exercise)
  - 1: Flat (minimal change)
  - 2: Downsloping (signs of an unhealthy heart)
- `ca` - Number of major vessels (0-3) colored by fluoroscopy
- `thal` - Thalium stress result:
  - 1,3: Normal
  - 6: Fixed defect (previous defect but now stable)
  - 7: Reversible defect (poor blood movement under stress)
- `target` - Presence of heart disease (1 = yes, 0 = no)

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/Smartlyfe21/heart-disease-classification.git
cd heart-disease-classification
pip install -r requirements.txt
```

## Usage

To explore the analysis and results, start Jupyter Notebook:

```bash
jupyter notebook
```

## Project Structure

```plaintext
heart-disease-classification/
├── data/                # Data files (raw and processed)
├── notebooks/           # Jupyter notebooks for analysis
├── scripts/             # Python scripts for data processing and modeling
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```

## Evaluation

If we can achieve at least **95% accuracy** in predicting heart disease cases, we will consider the project successful for further development.

## Results

The machine learning models trained in this project achieved strong performance in classifying heart disease cases. Key evaluation metrics include:

- **Accuracy**: XX%
- **Precision**: XX%
- **Recall**: XX%
- **F1-score**: XX%

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions, please contact [Smartlyfe21](https://github.com/Smartlyfe21).


  


