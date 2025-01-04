# Multi_Model_Based_Prediction_of_Covid_19_Data

## Overview
This repository contains the implementation of a group project for the course **WQD7003 - Data Science Project**. The aim of this project is to predict COVID-19 trends using multiple machine learning models. The project follows the CRISP-DM methodology and includes detailed data preprocessing, exploratory data analysis, model implementation, and result evaluation.

## Dataset
The dataset used in this project contains historical COVID-19 data, including infection rates, recoveries, and deaths across various regions. The data was preprocessed to handle missing values, normalize features, and prepare it for model training.

Dataset Source: [COVID-19 Dataset on Kaggle](https://www.kaggle.com/datasets/meirnizri/covid19-dataset)

## Methodology
We adhered to the CRISP-DM framework, which involves the following steps:
1. **Business Understanding**: Understanding the objectives of COVID-19 prediction and its potential impacts.
2. **Data Understanding**: Exploratory analysis of the dataset to identify trends and insights.
3. **Data Preparation**: Cleaning, transforming, and preparing the data for modeling.
4. **Modeling**: Implementing multiple machine learning algorithms.
5. **Evaluation**: Assessing the models' performance.
6. **Deployment**: Sharing insights and making predictions reproducible.

## Implementation
### Sections
The project notebook is divided into the following sections:
- **CRISP-DM**: Introduction and methodology breakdown.
- **Data Preprocessing**: Handling missing data, normalization, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Visualization and analysis of trends.
- **Machine Learning Modeling**: Implementing models such as linear regression, decision trees, and ensemble methods.
- **Result Evaluation and Interpretation**: Comparing model performances and interpreting results.

## Results
The models were evaluated based on metrics such as accuracy, precision, recall, and F1-score. The best-performing model demonstrated high predictive power and reliability in forecasting COVID-19 trends.


## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/multi-model-covid19-prediction.git
   ```
2. Install the required dependencies.
3. Open the notebook `WQD7003_Group_6_Multi_model_based_prediction_of_Covid_19_data.ipynb`.
4. Run the notebook cells sequentially.

## Dependencies
- Python 3.x
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- Jupyter Notebook

Install dependencies using:
```bash
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.
