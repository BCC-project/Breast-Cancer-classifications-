# Breast-Cancer-classifications
# Breast Cancer Classification Project

This project is designed to classify breast cancer as either **Benign** or **Malignant** using multiple machine learning models. The project includes data preprocessing, model training, evaluation, and deployment of the best-performing model.


---

## Overview

The goal of this project is to create an efficient machine learning pipeline for the classification of breast cancer. Multiple classifiers are trained, and the best-performing model is saved for predictions on new data.

---

## Dataset

The dataset used for this project is **breast_cancer_data_cleaned.csv**, which contains preprocessed data with relevant features:
- Features include radiographic data, mean texture, mean perimeter, etc.
- Target column: `diagnosis` (0 = Benign, 1 = Malignant).

---

## Installation

To run this project, clone the repository and install the required dependencies using the `requirements.txt` file.

```bash
# Clone the repository
git clone (https://github.com/BCC-project/Breast-Cancer-classifications-.git)

# Navigate to the project directory
cd breast-cancer-classification

# Install dependencies
pip install -r requirements.txt
