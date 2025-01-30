# Diabetes Prediction System using Machine Learning

## Overview
This project aims to predict diabetes using machine learning techniques. It utilizes a dataset containing medical information and applies various machine learning models to determine the likelihood of diabetes.

## Dataset
The dataset used for training and evaluation is `diabetes.csv`, which contains medical parameters such as glucose levels, blood pressure, BMI, and more.

### Features:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (1 = Diabetic, 0 = Non-Diabetic)

## Project Structure
- `Diabetes Prediction System using Machine Learning.ipynb`: Jupyter notebook containing data analysis, preprocessing, model training, and evaluation.
- `Diabetes Prediction System using Machine Learning-checkpoint.ipynb`: Auto-generated checkpoint file.
- `diabetes.csv`: Dataset used in this project.
- `README.md`: Project documentation.

## Requirements
To run this project, install the following dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction
```
2. Open the Jupyter notebook:
```bash
jupyter notebook "Diabetes Prediction System using Machine Learning.ipynb"
```
3. Run all cells to preprocess data, train models, and evaluate performance.

## Machine Learning Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## Results
The notebook evaluates models based on accuracy, precision, recall, and F1-score. The best-performing model is identified and can be used for diabetes prediction.

## Contributing
Feel free to fork this repository and improve the model or dataset preprocessing. Pull requests are welcome!

## License
This project is licensed under the MIT License.

