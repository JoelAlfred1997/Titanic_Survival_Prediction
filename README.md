
# Titanic Survival Prediction Using KNIME

This repository contains a KNIME workflow (`Titanic.knwf`) designed to predict passenger survival on the Titanic using machine learning techniques. The workflow demonstrates data preprocessing, feature engineering, and predictive modeling.

## Project Introduction

The Titanic Survival Prediction project analyzes the Titanic dataset to determine which passengers were likely to survive based on factors such as age, gender, ticket class, and more. This project showcases a machine learning approach implemented using the KNIME Analytics Platform, a visual workflow tool.

## Workflow Purpose

The purpose of this workflow is to:
1. Clean and preprocess the Titanic dataset.
2. Engineer features to enhance predictive accuracy.
3. Build and evaluate machine learning models (e.g., Logistic Regression, Random Forest) to predict survival.
4. Visualize results with charts and performance metrics.

## Instructions to Import the Workflow

Follow these steps to use the workflow in KNIME:

1. **Install KNIME Analytics Platform:**
   - Download and install [KNIME Analytics Platform](https://www.knime.com/downloads).

2. **Clone or Download the Repository:**
   - Clone this repository or download the `Titanic.knwf` file.

3. **Import the Workflow into KNIME:**
   - Open KNIME.
   - Go to `File` → `Import KNIME Workflow...`.
   - Choose `Select File` and locate the `Titanic.knwf` file.
   - Click `Finish` to load the workflow into KNIME.

4. **Configure the Workflow:**
   - Update the paths in the `CSV Reader` nodes to point to your local Titanic dataset file (e.g., `train.csv` from Kaggle).

5. **Execute the Workflow:**
   - Right-click each node and select `Execute` to run the workflow step by step, or execute the entire workflow by selecting `Execute All`.

## Dependencies and Configuration

To ensure smooth execution of the workflow:
1. **KNIME Extensions:**
   - Ensure the following KNIME extensions are installed:
     - KNIME Machine Learning Extensions
     - KNIME Statistics Extensions
     - KNIME Visualization Extensions

2. **Dataset:**
   - The workflow requires the Titanic dataset (e.g., `train.csv`). You can download it from [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic).

3. **KNIME Version:**
   - The workflow was created in KNIME version 4.x. Make sure your KNIME version is compatible.

## Results

The workflow includes:
- Preprocessing of the Titanic dataset (e.g., handling missing values, encoding categorical variables).
- Predictive modeling using Logistic Regression and Random Forest.
- Evaluation of model performance using metrics like Accuracy and ROC Curve.
- Visualizations such as bar charts and feature importance plots.

## Contributing

Feel free to fork this repository and contribute by:
- Adding new models or techniques.
- Improving preprocessing steps.
- Enhancing visualization and interpretability.
