# Heart Disease Prediction with Logistic Regression

This project builds a machine learning model to predict the presence of heart disease in patients based on clinical features. The model uses Logistic Regression and is trained on the well‑known UCI Heart Disease dataset.

## Features
- Binary classification (presence or absence of heart disease)
- ~85% accuracy on training data and ~80% on test data
- Can predict for a single new patient sample

## Dataset
The dataset contains 303 samples and 14 attributes:

- age : age in years
- sex : (1 = male, 0 = female)
- cp : chest pain type
- trestbps : resting blood pressure (mm Hg)
- chol : serum cholesterol (mg/dl)
- fbs : fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- restecg : resting electrocardiographic results
- thalach : maximum heart rate achieved
- exang : exercise induced angina (1 = yes, 0 = no)
- oldpeak : ST depression induced by exercise relative to rest
- slope : the slope of the peak exercise ST segment
- ca : number of major vessels (0–4) colored by fluoroscopy
- thal : thalassemia (0,1,2,3)
- target : (0 = no disease, 1 = disease)

The CSV file (`heart_disease_data.csv`) must be placed in the appropriate path. You can change the file path in the code if needed.

## Prerequisites
- Python 3.8 or higher
- Libraries listed in requirements.txt

## Installation & Usage

1. Clone the repository:
```bash
git clone https://github.com/rezamousavi9/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
