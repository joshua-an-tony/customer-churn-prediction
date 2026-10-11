# Online Shopping Customer Churn Prediction

## Project Overview

Customer churn refers to customers discontinuing their purchases or engagement with an online shopping platform. Identifying customers who are likely to churn enables businesses to understand customer behavior, improve retention strategies, and make data-driven decisions.

This project applies Data Science and Machine Learning techniques to analyze customer data, identify factors associated with churn, and predict whether a customer is likely to leave an online shopping platform.

## Objectives

- Analyze customer behavior and identify factors associated with churn.
- Perform data cleaning, preprocessing, and exploratory data analysis.
- Develop and compare multiple machine learning classification models.
- Evaluate model performance using appropriate classification metrics.
- Identify important features influencing customer churn.
- Apply explainable AI techniques to interpret model predictions.

## Technologies and Tools

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Gradient Boosting:** XGBoost, LightGBM
- **Model Explainability:** SHAP, LIME
- **Development Environment:** Jupyter Notebook, Anaconda

## Project Structure

```text
customer-churn-prediction/
|
|-- data/
|   |-- dataset.csv
|
|-- notebooks/
|   |-- data_preprocessing.ipynb
|   |-- exploratory_data_analysis.ipynb
|   |-- model_training.ipynb
|   |-- model_evaluation.ipynb
|
|-- visualizations/
|   |-- churn_distribution.png
|   |-- roc_curve.png
|   |-- confusion_matrix.png
|
|-- README.md
|-- requirements.txt
```

The directory structure is illustrative and should be updated to reflect the actual organization of the project.

## Methodology

### 1. Data Acquisition

Load the customer dataset and examine its structure, variables, data types, and metadata to understand the available information.

### 2. Data Preprocessing

- Identify and handle missing values and duplicate records.
- Encode categorical variables.
- Examine outliers and inconsistent values.
- Prepare features and the target variable.
- Split the dataset into training and testing sets.

### 3. Exploratory Data Analysis

Analyze customer characteristics and behavioral patterns using statistical summaries and visualizations. Examine the distribution of churn and investigate relationships between churn and relevant variables, such as customer satisfaction and complaints, where available.

### 4. Model Development

Train and compare the following classification algorithms:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- LightGBM

Use appropriate preprocessing and model validation procedures to ensure a reliable comparison.

### 5. Model Evaluation

Evaluate the trained models using the following metrics:

| Metric | Purpose |
|---|---|
| Accuracy | Measures the proportion of correctly classified observations. |
| Precision | Measures the proportion of predicted churn cases that are actual churn cases. |
| Recall | Measures the proportion of actual churn cases correctly identified. |
| F1-score | Represents the harmonic mean of precision and recall. |
| ROC-AUC | Measures the model's ability to distinguish between churn and non-churn classes. |
| Confusion Matrix | Summarizes correct and incorrect classifications for each class. |

Model selection will consider the business objective, class distribution, and the relative costs of false-positive and false-negative predictions.

### 6. Model Explainability

Apply SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations) to investigate the factors influencing model predictions.

These techniques provide global and individual prediction explanations, helping improve the interpretability of the model.

## Expected Outcomes

- Identification of customer characteristics associated with churn.
- Comparative evaluation of machine learning classification models.
- Identification of influential features using model interpretation techniques.
- Evidence-based insights to support customer retention strategies.
- A reproducible workflow for customer churn analysis and prediction.

## Installation and Execution

### Prerequisites

Ensure that Python and the required libraries are installed on your system.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/customer-churn-prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd customer-churn-prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the relevant notebooks and execute the cells in the appropriate order, beginning with data preprocessing.

## Dependencies

The project uses the following Python libraries:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
lightgbm
shap
lime
jupyter
```

These dependencies should be listed in the `requirements.txt` file. Package versions may be specified to support reproducibility.

## Limitations

- Model performance depends on the quality and representativeness of the available dataset.
- Predictions may not generalize to other online shopping platforms or customer populations.
- Feature importance and prediction explanations do not establish causal relationships.
- Performance metrics must be interpreted in the context of class imbalance and business requirements.

## Future Enhancements

- Develop an interactive dashboard for churn analysis.
- Deploy the selected model as a web application or API.
- Generate customer-level churn risk reports.
- Evaluate model performance on independent datasets.
- Investigate strategies for translating predictions into effective customer retention actions.

## Author

**Your Name**

GitHub: https://github.com/joshua-an-tony

## License

Unless otherwise specified, this project is intended for educational and research purposes. An appropriate license should be added if the project is distributed for reuse.
