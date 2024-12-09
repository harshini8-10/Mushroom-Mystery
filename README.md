# Title of the Project: Mushroom Mystery
 **Unveiling the Poisonous and Edible Mushrooms!**

# Kaggle Contest Achievement
Participated in Kaggle Competition 

Best MCC Score Achieved: 0.98440
Among the top contenders (1st score was 0.98514)

## Description  
"Mushroom Mystery" is a data science project focused on classifying mushrooms as either edible or poisonous based on their features. The project leverages machine learning techniques to develop a high-performing model for accurate predictions, aiding foragers and researchers alike.

The project showcases advanced classification techniques and evaluates model performance using the Matthews Correlation Coefficient (MCC) as the key metric.

## Goals
1. Develop Accurate Classifiers: Create models to differentiate between edible and poisonous mushrooms.
2. Handle Imbalanced Dataset: Employ strategies to handle any class imbalance effectively.
3. Feature Engineering: Extract meaningful insights from categorical and numerical features.
4. Achieve High MCC Score: Optimize models to maximize the Matthews Correlation Coefficient.
5. Participate in Kaggle Contest: Compete with other data scientists and secure a top rank.

## Key Files
Mushroom_Mystery.ipynb : The Jupyter Notebook with data processing, analysis, and model training code.

[DOWNLOAD FROM] [https://www.kaggle.com/competitions/playground-series-s4e8/data]
train.csv : Training dataset with target labels.

test.csv : Test dataset without target labels.

Mushroom3a.csv : Final predictions for Kaggle submission.

## Technologies Used
**Programming Language:** Python

**Libraries:** pandas, numpy, scikit-learn, lightgbm, xgboost, matplotlib, seaborn, and others.

## Dataset
### Train Dataset:

**Features:** 21 predictors (both categorical and numerical).

**Rows:** 1,048,574

**Target Variable:** Binary (class - e for edible, p for poisonous).

### Test Dataset:

**Features:** 21 predictors

**Rows:** 1,048,575

### Key Features:
**cap-diameter:** Diameter of the mushroom cap (numeric).

**cap-shape, cap-surface, cap-color:** Categorical features describing cap characteristics.

**gill-spacing, gill-attachment, gill-color:** Describing gill attributes.

**stem-height, stem-width, stem-color:** Numeric and categorical stem features.

**spore-print-color, habitat, season:** Environmental and lifecycle factors.

## Pre-requisites

**Library Installation**:  

Install the following libraries before running the script:  

!pip install pandas numpy scikit-learn lightgbm xgboost matplotlib seaborn category-encoders

## Script File  
`Mushroom Mystery.ipynb`  
- The Jupyter Notebook script contains all the steps for data preprocessing, feature engineering, machine learning model building, and application of same on test dataset for prediction

## How to Use

### 1. Prepare the Environment:
- Ensure the datasets (train.csv and test.csv) are in the same directory as the notebook.
- Install the required libraries using the command above.

### 2. Run the Notebook:
- Open Mushroom_Mystery.ipynb in Jupyter Notebook.
- Execute all cells sequentially to preprocess the data, train models, and evaluate results.

### 3. Generate Submission:
- The notebook outputs a file Mushroom3a.csv with predictions ready for Kaggle submission.

## Methodology

### Data Preparation:  
1. Load the dataset and handle missing values.
2. Perform encoding for categorical variables using techniques like one-hot encoding or target encoding.
3. Apply feature scaling to numeric columns.
4. Conduct Exploratory data analysis (EDA) for feature insights.

### Model Development:
1. Train multiple classifiers including LightGBM, CatBoost, and Random Forest.
2. Optimize hyperparameters using grid search or randomized search.
3. Evaluate performance using MCC and confusion matrix.
   
### Insights & Results:
Top Performing Individual Model: LightGBM with optimized hyperparameters.
But Ensemble of LightGBM, CatBoost & Random Forest resulted in best prediction with best MCC Score 0.98440.

## How to Use:  

**Clone the Repository**:  
   Clone this GitHub repository to your local machine.  
   git clone https://github.com/harshini8-10/Mushroom-Mystery
