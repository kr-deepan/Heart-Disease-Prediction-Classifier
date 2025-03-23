# Heart Disease Prediction Classifier

Using Binomial Regression

## Project Description

This project involves creating a machine learning model to predict the likelihood of a person having heart disease based on various health attributes. The model uses the **Logistic Regression** algorithm to classify whether a person is most likely to have heart disease (target = 1) or least likely (target = 0). The model is trained using the **Heart Disease Cleveland dataset**, which contains health-related attributes such as age, blood pressure, cholesterol levels, and more.

## Dataset

The dataset used in this project is **Heart_disease_cleveland.csv**. It contains health data for 303 patients, with the following attributes:

- **age**: Age of the person.
- **sex**: Gender (1 = male, 0 = female).
- **cp**: Chest pain type (categorical).
- **trestbps**: Resting blood pressure (mm Hg).
- **chol**: Serum cholesterol level (mg/dl).
- **fbs**: Fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false).
- **restecg**: Resting electrocardiographic results.
- **thalach**: Maximum heart rate achieved.
- **exang**: Exercise induced angina (1 = yes, 0 = no).
- **oldpeak**: Depression induced by exercise relative to rest.
- **slope**: Slope of the peak exercise ST segment.
- **ca**: Number of major vessels colored by fluoroscopy.
- **thal**: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversable defect).
- **target**: The target variable (1 = heart disease, 0 = no heart disease).

There are 303 instances and 14 features in total.

## Requirements

To run this project, you need to install the following libraries:

- `pandas`
- `numpy`
- `scikit-learn`

You can install these dependencies using `pip`:

```bash
pip install pandas numpy scikit-learn
