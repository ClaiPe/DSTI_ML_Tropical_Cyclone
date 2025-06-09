# 🌪️ Cyclone Intensity Classification using Machine Learning

## Course info

- **Institution:** DSTI School of Engineering
- **Program:** Applied MSc in Data Science & Artificial Intelligence  
- **Course:** Machine Learning with Python   
- **Project:** Group project 

---

## Overview
This project presents a machine learning pipeline developed to classify cyclone intensity levels based on environmental and geographical data. The goal is to predict the **TD9636_STAGE**, a framework for cyclone intensity stages, using features derived from the **IBTrACS dataset** provided by NOAA.
The project is structured to follow best practices in data preprocessing, model training, and evaluation, and is designed to handle real-world issues such as missing values and class imbalance.

---

## Dataset

 - **Source:** NOAA's IBTrACS Dataset
 - **Target variable:** TD9636_STAGE (Cyclone intensity stage)
 - **Features:** A selection of environmental and geographical attributes

---

## Pipeline Steps
1. Preprocessing
 - Textual data is transformed into numerical representations.
 - Empty cells and strings containing only spaces are handled to ensure clean input.
 - The target column is separated from the feature set.

2. Splitting
 - The dataset is split into 80% training and 20% testing subsets.
 
3. Handling Class Imbalance
 - SMOTE (Synthetic Minority Over-sampling Technique) is used to balance the training data.

4. Model Training and Testing
 - Multiple classification models are evaluated.
 - **GridSearchCV** is used for hyperparameter optimization.

5. Evaluation
 - Models are assessed using appropriate metrics depending on balance:
